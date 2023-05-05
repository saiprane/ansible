I have deployed Five hosts HAproxy, devA, devB, devC, bastion, and  devA, devB, and devC share load on the HAproxy host, which serves as the service's entry point.
bastion acts as a jump host in which it can be accessed by ssh key, bastion acts as secure access point.
the tasks are implemented using ansible and i have deployed flask app and curl dev A,devB,devC to HAproxy is successful.
the ip adressess of servers created are :
