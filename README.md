
![Ops Manager](images/forward-proxy.png)


* Usage
This tile can be used to deploy a http proxy by Ops Manager

* [Apache forward proxy bosh release](https://github.com/datianshi/apache-forward-proxy-boshrelease)

* Configuration

  * Configure the open port

    ![Ops Manager](images/port.png)

  * Configure the security

    ![Ops Manager](images/security.png)

    Proxy basic authentication with username and password

    Comma delimited network ranges that allowed in this proxy

* How to build this tile

```
gem install vara
vara build-metadata .
```     
