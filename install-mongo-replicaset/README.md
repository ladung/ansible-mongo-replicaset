
Inventory
---------


```
[primary]
PRIMARY_IP

[secondary]
SECONDARY_1_IP
SECONDARY_2_IP

[primary:vars]
db_user_admin_username=USER_ADMIN_USERNAME
db_user_admin_password=USER_ADMIN_PASSWORD
db_cluster_admin_username=CLUSTER_ADMIN_USERNAME
db_cluster_admin_password=CLUSTER_ADMIN_PASSWORD
db_user_name=DB_USERNAME
db_user_password=DB_PASSWORD
db_name=DB_NAME
```

Replicaset setup

```ansible-playbook -i inventory/ENVIRONMENT.ini main.yml```


