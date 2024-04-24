```bash
curl -X 'POST' 'http://ms00210-daat-api-af-it.apps.ocps.sviluppo.inps.it/api/v1/Repository' \
-H 'accept: application/json' \
-H 'Content-Type: application/json' \
-d '{
  "code": "MS30001",
  "mnemonicName": "devhub-poc-repo1",
  "macroAreaAbbreviation": "DAAT",
  "teamId": "9883de71-03ae-4e12-9c86-cd3ad072e174",
  "teamProjectId": "0b882d41-cc63-4668-9bb1-5730b7d35009"
```

```json
{
  "name": "POC_DeveperHubPrj_MS30001_devhub-poc-repo1",
  "id": "6a5ef32d-a4a2-4743-a1e7-a7da0fd8e645",
  "code": "MS30001",
  "mnemonicName": "devhub-poc-repo1",
  "isFork": false,
  "devOpsUrl": "https://azuredevops.servizi.inps/DAAT/POC_DeveloperHub/_git/POC_DeveperHubPrj_MS30001_devhub-poc-repo1"
}
```