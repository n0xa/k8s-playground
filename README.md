# k8s-playground
Some examples I'm making while getting started with k8s on ProxMox  
I like playing with WordPress as an onboarding-level project for clusters, because it requires pod networking, dynamic storage, and an externally-accessible service in order to work properly. It's more complicated than a generic nginx setup and forces you to troubleshoot.

storage
-------
Example configuration of deploying an NFS Client Provisioner to your custom k8s cluster  

wordpress
---------
Manifest files from the official wordpress kubernetes documentation. Deploys an ANCIENT (and probably vulnerable) WordPress instance.  

wp-helm
-------
My example configuration of a high-avaiable, database-replicated WordPress deployment that's pretty much enterprise-ready.
