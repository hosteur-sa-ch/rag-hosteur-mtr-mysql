**Replication Master-Master activated between Regions**

Use this login to connect to databases : 

Login : ${globals.db_user}
Password : ${globals.db_pass}


Manage the database nodes using the next credentials:

**phpMyAdmin Panel 1**: [https://${settings.envName}-MTR-1.${globals.domain-1}:8443](https://${settings.envName}-MTR-1.${globals.domain-1}:8443)   
**phpMyAdmin Panel 2**: [https://${settings.envName}-MTR-2.${globals.domain-2}:8443](https://${settings.envName}-MTR-2.${globals.domain-2}:8443)   
**Username**: ${globals.db_user}    
**Password**: ${globals.db_pass}