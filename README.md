**The application consists of a web app and a MongoDB database. The web app is pulled from a Docker repository, and both components connect using external configuration data stored in ConfigMaps and Secrets. The setup also makes the application accessible through a web browser.****
if you can't access the NodePort service webapp with MinikubeIP:NodePort, execute the following command:

<minikube service webapp-service>