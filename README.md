Initialise GCP CLI.
```
gcloud init
```
If not authorised yet,authorize with the below command !
```
gcloud auth login 
```
To check the configuration
```
gcloud config set
```
To list out the projects in sync with the CLI
```
loud projects list
```
Choose the required Project from the listed out items
```
gcloud config set project my-project-id
```
Deploy the application
```
gcloud app deploy(after configured) 
```
