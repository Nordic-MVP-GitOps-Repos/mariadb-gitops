# mariadb-gitops

Add secret for user/pw manually:
```
kind: Secret
apiVersion: v1
metadata:
  name: mariadb
stringData:
  database-user: <mysql user>
  database-password: <mysql pw>
  database-root-password: <mysql root pw>
  database-name: <database name>
```
