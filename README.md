# k8_project
Building and containerizing the micro-services
The two micro-services we will deploy here are called system and inventory. The system micro-service returns the JVM system properties of the running container and it returns the pod’s name in the HTTP header making replicas easy to distinguish from each other. The inventory micro-service adds the properties from the system micro-service to the inventory. This process demonstrates how communication can be established between pods inside a cluster.
