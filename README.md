This project follows a microservices architecture with around 13 branches, each representing a specific service. Every branch contains a Dockerfile and a Jenkinsfile, ensuring a streamlined CI/CD pipeline. The deployment process is fully automated using GitHub webhooks, which trigger Jenkins pipelines upon code commits or updates. Once triggered, Jenkins builds the respective microservice, creates a Docker image, tags it appropriately, and pushes it to the Docker registry. After the successful build, the pipeline automatically deploys the updated service to Amazon Elastic Kubernetes Service (EKS), ensuring seamless scaling, high availability, and efficient resource management. This approach enables continuous integration and deployment, reducing manual intervention and enhancing the reliability of the system.

![Screenshot 2024-04-15 at 2 48 51 PM](https://github.com/MytPraveen/Microservice/assets/160492814/b736e468-9940-463a-848c-d086d04397c2)
![Screenshot 2024-04-15 at 2 48 40 PM](https://github.com/MytPraveen/Microservice/assets/160492814/69da9f3c-9e31-427b-a3b1-b7d6e8c489a5)
![Screenshot 2024-04-15 at 2 48 24 PM](https://github.com/MytPraveen/Microservice/assets/160492814/717e0400-3a7e-4a35-aa10-69b6f4549985)
![Screenshot 2024-04-15 at 2 48 09 PM](https://github.com/MytPraveen/Microservice/assets/160492814/721df06d-009d-45bc-a932-b56eea915cda)
![Screenshot 2024-04-15 at 2 49 27 PM](https://github.com/MytPraveen/Microservice/assets/160492814/fd5bd4e5-2fd9-4b08-94cd-6b7be7465f71)




