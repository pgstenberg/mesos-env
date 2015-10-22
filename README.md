#Mesos-env

Helps to set up a Mesos environment with bash and docker.

###Examples

**Env on localhost**
``
bash <(curl -s https://raw.githubusercontent.com/pgstenberg/mesos-env/master/mesos-env) 127.0.0.1
``

**Master and Slave and bind to IP**
``
bash <(curl -s https://raw.githubusercontent.com/pgstenberg/mesos-env/master/mesos-env) IP
``

**Create slave and connect to master**
``
bash <(curl -s https://raw.githubusercontent.com/pgstenberg/mesos-env/master/mesos-env) IP slave MASTER_IP
``
