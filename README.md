# Containerization-WebApp

I have deployed a web application in a docker container image and running that image on Google Kubernetes Engine (GKE)cluster. After running it on cluster I have deployed the web application as a load-balanced set of replicas that can scale to the needs of your users(I took three users).


STEPS TAKEN: 

STEP 1: Activating 2 different API's i.e. Artificat Registry and Kubernetes Engine API and then activating the cloud shell. 
STEP 2: Creating a repository and selecting a REGION for the repository.

From STEP 1 & STEP 2 we will be able to store an image in Artifact Registry and deploy it from the registry.
<img width="1131" alt="Screenshot 2024-02-27 at 2 56 52 AM" src="https://github.com/sanyaarora27/Containerization-WebApp/assets/54741828/2b0954a5-14f2-4bf1-befb-e2b2970c17a9">

STEP 3: We'll build the container image and deploy the image on the port 8080.
<img width="1469" alt="Screenshot 2024-02-27 at 2 57 29 AM" src="https://github.com/sanyaarora27/Containerization-WebApp/assets/54741828/7eda0d8c-8a6e-424b-904f-539531b5bd2f">

Building a docker image from the docker file
IAM bind pollicy binding services which provides granular access controls for specific objects inside a cluster or namespace.
<img width="1465" alt="Screenshot 2024-02-27 at 2 58 08 AM" src="https://github.com/sanyaarora27/Containerization-WebApp/assets/54741828/cae4a4b9-2ab9-4cc7-9347-e97557dceca1">

STEP 4: Pushing the docker image to artifact registry.

STEP 5: Creating a Google kubernetes Engine(GKE) cluster and deploying the app to the GKE cluster.
<img width="1465" alt="Screenshot 2024-02-27 at 2 59 06 AM" src="https://github.com/sanyaarora27/Containerization-WebApp/assets/54741828/77399e71-01af-45ff-8af9-b468848667cc">

and the final step,
STEP 6: Creating a ClusterIP by the name LoadBalancer.
After this step pods are exposed to external IP address.
<img width="1466" alt="Screenshot 2024-02-27 at 2 59 49 AM" src="https://github.com/sanyaarora27/Containerization-WebApp/assets/54741828/3552bbb6-a759-495d-98bb-0ae1ec61584b">


<img width="864" alt="Screenshot 2024-02-27 at 3 04 37 AM" src="https://github.com/sanyaarora27/Containerization-WebApp/assets/54741828/79453ad6-3631-4c45-9e76-74d1ae4b9733">

REFERENCES:
CLOUD.GOOGLE/KUBERNETES/DOCS/

