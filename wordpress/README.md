
#Create a Secret for MySQL Password
A Secret is an object that stores a piece of sensitive data like a password or key. The manifest files are already configured to use a Secret, but you have to create your own Secret. Note: To protect the Secret from exposure, neither get nor describe show its contents.

#Create the Secret object from the following command:

`kubectl create secret generic mysql-pass --from-file=password.txt`

#Deploy WordPress and MySQL from the wordpress-mysql.yaml file:

`kubectl create -f wordpress-mssql.yaml`