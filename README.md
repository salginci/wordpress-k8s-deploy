# wordpress-k8s-deploy
Deploy Wordpress on Kubernetes with Mysql

First Generate a secret on kubernetes to keep mysql password

kubectl create secret generic salginci-home-mysql-secret --from-literal=password='mypassword'

Then 
deploy mysql yaml
and then deploy wordpress yaml.
Specifically you can assign ssl and domain .


For detailed explanation you may want to check: 

https://medium.com/@salginci/deploying-wordpress-on-google-cloud-platform-a-journey-to-app-modernization-part-1-75b1d78502cf

