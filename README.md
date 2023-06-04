# simple_microservices_demo 
Demo of Microservices in Kubernetes using Python Flask in *Linux OS*

[![Watch the video](https://img.youtube.com/vi/SdTzwYmsgoU/default.jpg)](https://www.youtube.com/watch?v=SdTzwYmsgoU)


Steps to automate the microservices deployment in K8s
- Installing Python 3
- Creating Python Virtual Environments
Install the venv
```
pip install virtualenv
```
Create the venv
```
virtualenv venv_name
```
Run the venv
```
source venv_name/bin/activate
```
- Install Flask Application
```
pip install Flask
```
- Using Pip to Freeze Python Dependencies

```
pip freeze requirements.txt
```
- Building the docker image using Dockerfile
- Writing Docker Compose file
```
minikube service service_name
```
- Writing Kubernetes Manifest files for the application
- Creating Helm Chart
