Key to Opencontrail provided network in Kubernetes
==================================================

Here are the steps to get access to the opencontrail network enabled kubernetes cluster

1-> Download the key file sanjus.key  
2-> chmod 400 sanjus.key  
3-> ssh -i sanjus.key -l sanjua **IP**, of the kubernetes master, minion and gateway  


Follow the same for anikets.key to access another cluster

Check out the guestbook-go app pod annotations under /home/sanju  

Go deploy apps! Enjoy!
