ASSIGNMENT-4 NAME:R.Aswin Vishal Kumar V M REGNO:715519104303

1.	Pull an Image from docker hub and run it in docker playground.

![image](https://user-images.githubusercontent.com/99410043/202616880-a72dad11-c227-4f22-b5f8-150bbe33e172.png)
2.	Create a docker file for the job portal application and deploy it in Docker desktop application.

*Create docker file. Name as Dockerfile (without exetension) in your website code location
![image](https://user-images.githubusercontent.com/99410043/202616913-0eb2246c-c87a-4941-b1b0-211f4b5438f2.png)

*build images using this command


docker build -t (filename as you create) . --no-cahe


Example: docker build -t job-portal-app. --no-cahe
![image](https://user-images.githubusercontent.com/99410043/202616934-d7358c4f-8770-4b94-9072-f9577ceaa544.png)

*run dockerfile using command
docker run -p 3000:5000 job-portal-app

*	you will get output in browser type “localhost:3000”

![image](https://user-images.githubusercontent.com/99410043/202616978-c4a59336-2074-4c8f-aea0-24522424ad4c.png)
![image](https://user-images.githubusercontent.com/99410043/202616997-d206eb0e-6e2d-4ab0-a358-1301af9b89d0.png)
![image](https://user-images.githubusercontent.com/99410043/202617007-6223fc0a-8ed6-4239-84c2-a6d2f2618811.png)
![image](https://user-images.githubusercontent.com/99410043
![image](https://user-images.githubusercontent.com/99410043/202617082-e3e3a660-619b-4058-9c0c-50f5e16144a5.png)
*Login to dockerhub and see the docker pushed file


3.	Create a IBM container registry and deploy helloworld app or jobportalapp.

*open command promt and follow the command in  below images
/202617016-9457221d-3d3e-4cbc-9019-fdd28b778bda.png)

![image](https://user-images.githubusercontent.com/99410043/202617030-29930b48-739e-4a61-ab42-f546d23da136.png)
![image](https://user-images.githubusercontent.com/99410043/202617045-ab838f90-8ee4-4764-b2ae-bc2bdfe986e8.png)
*push the file into docker use this command docker push repositroyname/imagename example:docker vishnuhero2001/job-portal-app
![image](https://user-images.githubusercontent.com/99410043/202617138-a89bfb49-a2e7-4bfa-aa83-e39374734746.png)
*Login to dockerhub and see the docker pushed file

4.	Create a Kubernetes cluster in IBM cloud and deploy helloworld image or jobportal image and also expose the same app to run in nodeport.
*login to ibmcloud
*	Create a Kubernetes cluster
*go to Kubernetes dashboard
*create a new one
![image](https://user-images.githubusercontent.com/99410043/202617165-1f658f9f-f589-4afd-8cc8-e0a4114b865d.png)

*go to services
![image](https://user-images.githubusercontent.com/99410043/202617198-219a212b-9e75-4902-864f-f62c7a5867cf.png)
*click edit option to see the yaml file
![image](https://user-images.githubusercontent.com/99410043/202617228-2b7a4a0a-c52c-4426-a4a3-6efef7fa6b3c.png)
*delopyment id
![image](https://user-images.githubusercontent.com/99410043/202617244-024a1087-9697-4cbd-a8af-1111b4082581.png)

Copy the ip and port numer
![image](https://user-images.githubusercontent.com/99410043/202617307-52875217-784f-47cf-8bc3-b451f8f9213e.png)
*paste the ip and port numer in browser 

output screen
![image](https://user-images.githubusercontent.com/99410043/202617348-43b28842-f086-4b5e-835d-492024ee07df.png)
![image](https://user-images.githubusercontent.com/99410043/202617373-796bc503-e840-438b-8d30-0ccf894687d2.png)
![image](https://user-images.githubusercontent.com/99410043/202617386-f2a45915-a96d-4977-9c64-6642df92d011.png)
![Uploading image.png…]()










3.	Create a IBM container registry and deploy helloworld app or jobportalapp.

*open command promt and follow the command in  below images

