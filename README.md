# KickstartAngular

## Version Details
```
node = v14.19.0
npm = 8.5.2
angular-cli = 12.2.16
```

## Running the Project

```
ng serve
```

The above command will start the server at http://localhost:4200/

## Tasks

### Task 1 - Running Application Locally

1. Fork this repository.
2. Checkout the development branch on your local machine.
3. Do research on how to install angular dependencies and install them.
4. Test the application locally and verify it's running at http://localhost:4200/

### Task 2 - Create a CI/CD Pipeline in Azure DevOps and deploy to service of your choice

1. Create a feature branch named "feature/ado-cicd" and checkout to this new branch.
2. Create a Build pipeline.
3. Publish artifacts.
4. Create a Release Pipeline and consume the artifacts.
5. Deploy to service of your choice (Web App, Azure VM, Azure Blob).
6. Test the application.

### Task 3 - Containerize the application

1. Checkout to a new feature Branch "feature/docker".
2. Create a Dockerfile.
3. Create a Build pipeline.
3. Build the image using CI.
4. Tag the image with proper name. (AVOID USING "latest". Use Semantic Versioning. eg "v1.0.0". So the image name should be like "xxxxxx/yyyyyy:v1.0.0").
5. Push the image to container registry of your choice.
6. Create a release pipeline and deploy to ACI (Azure Container Registry).

## RULES!!!

- You have to strictly follow the branching method. Working on master or development branch is STRICTLY FORBIDDEN!
- EACH TASK IS TO BE DOCUMENTED ALONG WITH SCREENSHOTS. DOCUMENTATION IS EQUALLY VALUABLE AS THE IMPLEMENTATION ITSELF.