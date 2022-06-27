# New approaches for distributed data analysis with the DASF Messaging Framework

_Data Science Symposium No. 7, June 2022_

**Authors:** Sommer, Philipp Sebastian, Eggert, D., Wichert, V., Baldewein, L., Dinter, T., Werner, C.

---

The Data Analytics Software Framework (DASF, https://doi.org/10.5880/GFZ.1.4.2021.004 ) supports scientists to conduct data analysis in distributed IT infrastructures by sharing data analysis tools and data. For this purpose, DASF defines a remote procedure call (RPC) messaging protocol that uses a central message broker instance. Scientists can augment their tools and data with this protocol to share them with others or re-use them in different contexts.

Our framework takes standard python code developed by a scientist, and automatically transforms the functions and classes of the scientists code into an abstract layer. This abstraction, the server stub as it is called in RPC, is connected to the message broker and can be accessed by submitting JSON-formatted data through a websocket in the so-called client stub. Therefore the DASF RPC messaging protocol  in general is language independent, so all languages with Websocket support can be utilized. As a start DASF provides two ready-to-use  language bindings for the messaging protocol, one for Python and one for  the Typescript programming language.

DASF is developed at the GFZ German Research Centre for Geosciences and was funded by the Initiative and Networking Fund of the Helmholtz Association through the Digital Earth project (https://www.digitalearth-hgf.de/). In this talk, we want to present the framework with some simple examples, and present two new approaches for the framework. One is an alternative light-weight message broker based on the python web-framework Django, that supports containerization, user-management and token authentification. The other one is an approach for easily applicable end-to-end-encryption in the messaging framework and user-authentification in the backend module for secure federation of data analysis between research centers.


## Files
- [basic.ipynb](basic.ipynb) is a small example to demonstrate the high-level
  API of the de-messaging-python framework


## Note

The source code for the DASF Messaging Framework is open-source at
https://git.geomar.de/digital-earth/dasf/dasf-messaging-python

This talk is an adaption of the talk at the EGU 2021:

> Sommer, P. S., Wichert, V., Eggert, D., Dinter, T., Getzlaff, K., Lehmann, A., Werner, C., Silva, B., Schmidt, L., and Schäfer, A.: A new distributed data analysis framework for better scientific collaborations, EGU General Assembly 2021, online, 19–30 Apr 2021, EGU21-1614, https://doi.org/10.5194/egusphere-egu21-1614, 2021.


## Acknowledgements

This work has been created as part of the Working Group for Distributed Data Analysis within the HGF initiative DataHub, and Digital Earth.


## License

The contents of this repository is published under the Creative Commons
Attribution 4.0 International Public License (CC BY 4.0).

See the [LICENSE](LICENSE) file for more details.

Copyright (c) 2022, Philipp S. Sommer, Hereon.
