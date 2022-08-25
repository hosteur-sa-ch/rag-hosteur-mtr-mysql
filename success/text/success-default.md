**MySQL 1**: [https://${settings.envName}-MTR-1.${globals.domain-1}/](https://${settings.envName}-MTR-1.${globals.domain-1}/)   
**MySQL 2**: [https://${settings.envName}-MTR-2.${globals.domain-2}/](https://${settings.envName}-MTR-2.${globals.domain-2}/)

Connect to database with 

${settings.envName}-MTR-1.${globals.domain-1} for application in Region 1
${settings.envName}-MTR-2.${globals.domain-2} for application in Region 2

Use this login to connect to databases : 

Login : ${globals.db_user}
Password : ${globals.db_pass}
