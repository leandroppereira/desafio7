O projeto mydb deve possui um banco de dados mysql.
o banco de dados deve ser gerado a partir dos templates:
mysql-template.json
mysql-template.yaml

- O projeto deve ter o template instalado
- O template deve possuir um parametro customizado chamado "CUSTOM_PARAMETER", com o valor "custom".
- O tempate possui um parametro NAMESPACE. O valor deve ser igual a mydb
- Sua aplicação deve funcionar com:
- com memória de 512Mi
- O data base service name deve ser servicedb
- O usuário deve ser user1
- O password deve ser pass1 
- O root password deve ser rootpass1
- O mysql database name deve ser mysqldb
- A versão do mysql deve ser 8.0-el8
- os recursos devem ter um label chamado db com valor mysql
- sua aplição deve ter o nome mysqldb
