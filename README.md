# cloud-sql-test
---
Instructions:
1. ```cf push --no-start```
2. ```cf bind-service cloud-sql-test gcp-sql -c '{"role":"cloudsql.editor"}'```
3. ```cf start cloud-sql-test```
