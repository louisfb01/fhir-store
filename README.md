To load the Synthea dataset, open the DevBox console and execute the following REST query:

```
POST /fhir/$load
Accept: text/yaml
Content-Type: text/yaml

source: 'https://storage.googleapis.com/aidbox-public/synthea/100/all.ndjson.gz'
```