# FIWARE Short Time Historic (aka. Comet)

[![License badge](https://img.shields.io/badge/license-AGPL-blue.svg)](https://opensource.org/licenses/AGPL-3.0)
[![Documentation badge](https://readthedocs.org/projects/fiware-sth-commet/badge/?version=latest)](http://fiware-sth-commet.readthedocs.org/en/latest/?badge=latest)
[![Docker badge](https://img.shields.io/docker/pulls/fiware/sth-commet.svg)](https://hub.docker.com/r/fiware/sth-commet/)
[![Support badge]( https://img.shields.io/badge/support-sof-yellowgreen.svg)](http://stackoverflow.com/questions/tagged/fiware-sth-comet)
[![Join the chat at https://gitter.im/telefonicaid/fiware-sth-comet](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/telefonicaid/fiware-sth-comet?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The **Short Time Historic (STH, aka. Comet)** is a component of the [FIWARE](https://www.fiware.org/) ecosystem in charge of managing (storing and retrieving) historical raw and aggregated time series information about the evolution in time of context data (i.e., entity attribute values) registered in an [Orion Context Broker](https://github.com/telefonicaid/fiware-orion) instance.

All the communications between the STH and the Orion Context Broker as well as between the STH and any third party (typically for data retrieval) use standardized NGSI9 and [NGSI10](http://technical.openmobilealliance.org/Technical/technical-information/release-program/current-releases/ngsi-v1-0) interfaces.

For further information, please visit the component documentation at: http://fiware-sth-comet.readthedocs.io/en/latest/

<u>Note:</u> You can also navigate the [`docs/readthedocs`](./docs/readthedocs) directory in this very Github repository to access the STH component documentation.
