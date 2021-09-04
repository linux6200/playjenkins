# playjenkins
Jenkins Playground


# create secret in kubernetes
# kubectl create secret docker-registry regcred --docker-server=<your-registry-server> --docker-username=<your-name> --docker-password=<your-pword> --docker-email=<your-email>

kubectl create secret docker-registry regcred --docker-server="https://index.docker.io/v1/" --docker-username='linux6200' --docker-password='P@ssw0rd' --docker-email='guozb@msn.com'