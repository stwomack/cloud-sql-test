# cloud-sql-test
---
Instructions:
1. ```cf create-service google-cloudsql-mysql mysql-db-f1-micro cloud-sql-test```
2. ```cf push --no-start```
3. ```cf bind-service cloud-sql-test cloud-sql-test -c '{"role":"cloudsql.editor"}'```
4. ```cf start cloud-sql-test```
