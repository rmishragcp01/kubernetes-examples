Kuberenetes has taken the world of computing by storm! Now, what is Kubernetes anyways? In pure and simple words, Kubernetes is a type of container orchestrator and management platform, if you are into cloud native application development, microservices, distributed architectures which scales horizontally and utilize your cloud infrastructure in an efficient, optimal and elastic manner, you would possibly be dealing with containers already, so why do we need a container orchestrator?
  
  Without going into details of containers here (as this is about Kuberenets and I assume that you have some familiarty with containers already), think of containers as your standards of building, deploying and shipping the software to production, now you have 100s or 1000s of containers in no time, how are you going to manage them? How are you going to control them as individual units of deployment? How about their lifecycle management? How about securing them? How about loadbalancing between them? How about scaling them in or out when your load demand varries? Well, too many "hows" here and this certainly is not the end.
  
  This is where Kuberenets comes in, to give you control over your containerized applications in every aspect without having to deal with lower level details of containers themselves, you interact with Kubernetes APIs and rest is taken care by Kubernetes. Kuberenets evolved at Google and was later open sourced, today it's the defacto standard of container orchestration platform. Any public cloud, you name it..AWS, Google Cloud or MS Azure, they all have adopted Kuberenets as the force behind their managed Kuberenets service offerings.
  
  Well, I am a google cloud fan boy and therefore admire GKE a lot, GKE is Google's Kubernetes PaaS or CaaS offering, therefore I have tested if not all then most of the examples in this repo against GKE, some examples are left open ended and are subjective, but just because I tested them on GKE, does not mean you can not run these YAML files on ECS or AKS, off course you can.
  
Enjoy trying them out or pick up a good book, or tutorial which teaches you the concept and when you are ready to do some hands-on, please do keep my repository in mind.

Regards,
Rohit Mishra.
