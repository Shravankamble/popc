# *popc* (pods python client)

popc is a lightweight cli written in python to get pods info such as pods ip, name etc. 

# requirements

inorder to use this cli you have to have kubernetes client for python and rich library installed locally
if you don't have it installed already use below command to install both the library locally

cmd : ```pip3 install kubernetes rich```

# usage 

popc currently only takes one arguement which is ``` namespace ``` 

cmd : ``` popc kube-system ```
