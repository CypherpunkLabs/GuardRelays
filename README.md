# GuardRelays


Guard/Relay repo, this is how we make our baseline os used for the template.


# What is this?

A simple torrc configuration we use for our Guard/Middle relays in the tor network. 


Requirements:

Tor installed 



How would you install this? Example from fedora


``` 
yum install tor obfs4 -y 

```

Changes you should make to this torrc from this repository:

Modify Nickname, to one of your liking.

Change ContactInfo to your email of choice. 

That is it. 

Start and enable service. Guard/Middle relay setup. Thanks for helping the Tor network and it's users.

Feel free to run this on your home network, as these relays are not used for outbound traffic of the Tor network.

We also provide them as a service but the more the merrier. 
