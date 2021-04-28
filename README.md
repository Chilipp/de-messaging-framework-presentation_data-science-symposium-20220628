# A new distributed data analysis framework for better scientific collaborations

_vEGU21: Gather Online, April 28th, 2021_

[![DOI](https://img.shields.io/badge/DOI-10.5194%2Fegusphere--egu21--1614-blue)](https://doi.org/10.5194/egusphere-egu21-1614)

**Authors:** Philipp S. Sommer, Viktoria Wichert, Daniel Eggert, Tilman Dinter,
Klaus Getzlaff, Andreas Lehmann, Christian Werner, Brenner Silva,
Lennart Schmidt, and Angela Schäfer

---

A common challenge for projects with multiple involved research institutes is a well-defined and productive collaboration. All parties measure and analyze different aspects, depend on each other, share common methods, and exchange the latest results, findings, and data. Today this exchange is often impeded by a lack of ready access to shared computing and storage resources. In our talk, we present a new and innovative remote procedure call (RPC) framework. We focus on a distributed setup, where project partners do not necessarily work at the same institute, and do not have access to each others resources.

We present the prototype of an application programming interface (API) developed in Python that enables scientists to collaboratively explore and analyze sets of distributed data. It offers the functionality to request remote data through a comfortable interface, and to share and invoke single computational methods or even entire analytical workflows and their results. The prototype enables researchers to make their methods accessible as a backend module running on their own infrastructure. Hence researchers from other institutes may apply the available methods through a lightweight python or Javascript API. This API transforms standard python calls into requests to the backend process on the remote server. In the end, the overhead for both, the backend developer and the remote user, is very low. The effort of implementing the necessary workflow and API usage equalizes the writing of code in a non-distributed setup. Besides that, data do not have to be downloaded locally, the analysis can be executed “close to the data” while using the institutional infrastructure where the eligible data set is stored.

With our prototype, we demonstrate distributed data access and analysis workflows across institutional borders to enable effective scientific collaboration, thus deepening our understanding of the Earth system.

This framework has been developed in a joint effort of the DataHub and Digitial Earth initiatives within the Research Centers of the Helmholtz-Gemeinschaft Deutscher Forschungszentren e.V.  (Helmholtz Association of German Research Centres, HGF).


## Files
- [20210428-SommerP-de-messaging-framework.pdf](20210428-SommerP-de-messaging-framework.pdf) is the main presentation
- [basic.ipynb](basic.ipynb) is a small example to demonstrate the high-level
  API of the de-messaging-python framework

Note that the source for this talk, de-messaging-python, is (unfortunately)
still closed source, so you won't be able to run these examples yourself
(unless you're a member of Digital Earth or the Working Group for Distributed
Data Analysis within Datahub). We are working hard to release the code and it
will then be linked in this Github repository.

## Note

This talk is an adaption of the talk on the 5th Data Science Symposium 2021,
and the presentation at the Series of Online Research Software Events 2021,
namely

- Sommer, Philipp S., Wichert, Viktoria, Eggert, Daniel, Dinter, Tilman, Getzlaff, Klaus, Lehmann, Andreas, … Schäfer, Angela. (2021, January). Distributed data analysis for better scientific collaborations (Version v1.0). Presented at the 5th Data Science Symposium, Zenodo. http://doi.org/10.5281/zenodo.4456787
- Philipp S. Sommer, Viktoria Wichert, Daniel Eggert, Tilman Dinter, Klaus Getzlaff, Andreas Lehmann, … Angela Schäfer. (2021). A new distributed data analysis framework for better scientific collaborations. Presented at the International Series of Online Research Software Events (SORSE), Zenodo. http://doi.org/10.5281/zenodo.4575652

please cite it as follows:

> Sommer, P. S., Wichert, V., Eggert, D., Dinter, T., Getzlaff, K., Lehmann, A., Werner, C., Silva, B., Schmidt, L., and Schäfer, A.: A new distributed data analysis framework for better scientific collaborations, EGU General Assembly 2021, online, 19–30 Apr 2021, EGU21-1614, https://doi.org/10.5194/egusphere-egu21-1614, 2021.


## Acknowledgements

This work has been created as part of the Working Group for Distributed Data Analysis within the HGF initiative DataHub, and Digital Earth.


## License

The contents of this repository is published under the Creative Commons
Attribution 4.0 International Public License (CC BY 4.0).

See the [LICENSE](LICENSE) file for more details.

Copyright (c) 2021, Philipp S. Sommer, Hereon.
