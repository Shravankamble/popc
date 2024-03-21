# *popc* (pods python client)

<i>popc is a lightweight cli written in python to get pods info such as pods ip, name etc.</i> 

# requirements

*inorder to use this cli you have to have kubernetes client for python and rich library installed locally*
*if you don't have it installed already use below command to install both the library locally*

cmd : ```$ pip3 install kubernetes rich```

*you can use the other approach by simply installing the install_popc file and make it executable and run it* 

```$ wget "https://raw.githubusercontent.com/Shravankamble/scripts/main/install_popc" ```

```$ sudo chmod +x install_popc ```

``` $ ./install_popc ```

***or you can use*** 

```$ bash install_popc ```

# usage 

popc currently only takes one arguement which is ``` namespace ``` 

cmd : ```$ popc kube-system ```
