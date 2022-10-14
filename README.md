# FHIR data store

### Overview

- **Description:** This repository deploys [DevBox/AidBox](https://github.com/Aidbox/devbox), a FHIR database server.
- **Primary author(s):** Louis Mullie [[@louism](https://github.com/louismullie)].
- **Contributors:** none.
- **License:** The code in this repository is released under the GNU General Public License, V3.

### Usage

To load the Synthea dataset, open the DevBox console and execute the following REST query:

```
POST /fhir/$load
Accept: text/yaml
Content-Type: text/yaml

source: 'https://storage.googleapis.com/aidbox-public/synthea/100/all.ndjson.gz'
```
