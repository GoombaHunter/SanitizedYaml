# SanitizedYaml
Here are some samples of Kubernetes, Docker, and Docker swarm configurations from my home lab and personal cloud.  Most of these are stored privately in AWS CodeCommit and shouldn't be publicly visible.  But as I get time I'll remove sensitive information and post some samples here for employers.

# About running Kubernetes and Docker Swarm.
Once upon a time I thought it would be a good idea to run Kubernetes at home.  I tried many different configurations and ran them all for months or years.  Here are some interesting configurations:

- Hybrid Kubernetes with two nodes at home and one in AWS (over a VPN connection)
- Hybrid Kubernetes with one node at home, one node on digitalocean and one node in AWS
- One docker swarm cluster at home and another in AWS
- Regular docker containers at home running on 3 nodes, one 5 node docker swarm cluster in AWS


I ran services like NextCloud, plex, smtp, xmpp, as well as supporting services like OpenLDAP or MySQL.  I tried a few variations on kubernetes including Rancher 2.0.

Now I'm using plain AWS services as running so many nodes in AWS was costing me over $100/mo and I have different financial priorities given the uncertainties of COVID and the time commitments required by my current contract.

At home I have a very nice lab running Proxmox since it's easy to use and k8s/swarm was well into overkill for what I need.
