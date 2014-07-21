#DNS configuration with OVH
We will see how to configure the DNS with [OVH](http://www.ovh.com).

At the location of the DNS zone configuration, set up edit of text, and use [configuration DNS standard](/dns_config).

###Dynamic IP:

Follow this part if you havea dynamic IP.

To find out if your internet provider provided you with a dynamic IP see here: (/isp).


Start by creating a username dynhost.

It should be added in the configuration file: 

Follow [this tutorial (french)](http://blog.developpez.com/brutus/p6316/ubuntu/configurer_dynhost_ovh_avec_ddclient) to the intallation of ddclient.
ddclient ad to OVH IP change. OVH'll then change your IP.

It should be added in the configuration file:
* your username and dynhost password 
* your domain name
