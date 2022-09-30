# Site store stub

### Overview

- **Description:** This repository implements a stub FHIR database service ([DevBox](https://github.com/Aidbox/devbox)) that can be used in lieu of the full [site store](https://github.com/coda-platform/site-store) service for development purposes.
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
