# A new distributed data analysis framework for better scientific collaborations

_International Series of Online Research Software Events (SORSE), March 3rd, 2021_

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4575652.svg)](https://doi.org/10.5281/zenodo.4575652)

**Authors:** Philipp S. Sommer, Viktoria Wichert, Daniel Eggert, Tilman Dinter,
Klaus Getzlaff, Andreas Lehmann, Christian Werner, Brenner Silva,
Lennart Schmidt, Angela Schäfer

A common challenge for projects with multiple involved research institutes is a well-defined and productive collaboration. All parties measure and analyze different aspects, depend on each other, share common methods, and exchange the latest results, findings, and data. Today this exchange is often impeded by a lack of ready access to shared computing and storage resources. In our talk, we present a new and innovative remote procedure call (RPC) framework. We focus on a distributed setup, where project partners do not necessarily work at the same institute, and do not have access to each others resources.
We present an application programming interface (API) developed in Python that enables scientists to collaboratively explore and analyze sets of distributed data. It offers the functionality to request remote data through a comfortable interface, and to share and invoke single computational methods or even entire analytical workflows and their results. The prototype enables researchers to make their methods accessible as a backend module running on their own infrastructure. Hence researchers from other institutes may apply the available methods through a lightweight python or Javascript API.  In the end, the overhead for both, the backend developer and the remote user, is very low. The effort of implementing the necessary workflow and API usage equalizes the writing of code in a non-distributed setup. Besides that, data do not have to be downloaded locally, the analysis can be executed "close to the data" while using the institutional infrastructure where the eligible data set is stored.
With our prototype, we demonstrate distributed data access and analysis workflows across institutional borders to enable effective scientific collaboration.
This framework has been developed in a joint effort of the DataHub and Digitial Earth initiatives within the Research Centers of the Helmholtz Association of German Research Centres, HGF.


## Files
- [20210303-SommerP-de-messaging-framework.pdf](20210303-SommerP-de-messaging-framework.pdf) is the main presentation
- [basic.ipynb](basic.ipynb) is a small example to demonstrate the high-level
  API of the de-messaging-python framework

Note that the source for this talk, de-messaging-python, is closed source
(so far), so you won't be able to run these examples yourself (unless you're a
member of Digital Earth or the Working Group for Distributed Data Analysis
within Datahub). If you are
interested, please get in touch with me (Philipp S. Sommer from HZG).

## Note

This talk is an adaption of the talk on the 5th Data Science Symposium 2021,
namely

> Sommer, Philipp S., Wichert, Viktoria, Eggert, Daniel, Dinter, Tilman, Getzlaff, Klaus, Lehmann, Andreas, … Schäfer, Angela. (2021, January). Distributed data analysis for better scientific collaborations (Version v1.0). Presented at the 5th Data Science Symposium, Zenodo. http://doi.org/10.5281/zenodo.4456787

please cite it as following:

> Philipp S. Sommer, Viktoria Wichert, Daniel Eggert, Tilman Dinter, Klaus Getzlaff, Andreas Lehmann, … Angela Schäfer. (2021). A new distributed data analysis framework for better scientific collaborations. Presented at the International Series of Online Research Software Events (SORSE), Zenodo. http://doi.org/10.5281/zenodo.4575652

or use the different formats provided at http://doi.org/10.5281/zenodo.4575652


## Acknowledgements

This work has been created as part of the Working Group for Distributed Data Analysis within the HGF initiative DataHub, and Digital Earth.


## License

The contents of this repository is published under the Creative Commons
Attribution 4.0 International Public License (CC BY 4.0).

See the [LICENSE](LICENSE) file for more details.

Copyright (c) 2021, Philipp S. Sommer, HZG.
