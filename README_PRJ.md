Steps to be performed in the project:
1. Push the change to the GitHub repository. Github action (or CodeBuild) will automatically build an image and push it to AWS ECR.
2. Create a EKS Cluster and Node Group.
3. Create a PostgreSQL Database service and use port-forwarding to seed data.
4. Create a configuration file for the API: corworking.yaml
5. Create configuration file for the database: configmap.yaml 
6. Deploy application "kubectl apply -f <file_config>".
7. Check status of application