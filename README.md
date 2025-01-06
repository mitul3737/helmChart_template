# helmChart_template

Let's install a wordpress application using [artifact](https://artifacthub.io/packages/helm/bitnami/wordpresshttps://artifacthub.io/packages/helm/bitnami/wordpress)

or search it using terminal

hub search hub wordpress


Let's follow the one from artifact
helm repo add bitnami https://charts.bitnami.com/bitnami
helm install my-wordpress bitnami/wordpress --version 24.1.5

Here we have  created a release called my-wordpress. Check the list of release

helm list


# Uninstall the release
helm uninstall my-wordpress

# Read the blog for more
(Blog)[https://mitul-shahriyar.hashnode.dev/all-about-helm]