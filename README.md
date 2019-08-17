# cloud-sql-test
---
Instructions:
```cf push --no-start```
```cf bind-service cloud-sql-test gcp-sql -c '{"role":"cloudsql.editor"}'```
```cf start cloud-sql-test```
