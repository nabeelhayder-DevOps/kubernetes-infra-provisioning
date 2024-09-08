# kubernetes-infra-provisioning
This repo contains the terraform code to provision infrastructure for the kubernetes which can be found in other repo i created by the name kubernetes-the-hard-way



## Instructions:
1. Go to the gcp directory and run `terraform init`.
2. Download service account credentials for you project from GCP console https://console.cloud.google.com/apis/credentials/serviceaccountkey and move it into the gcp directory.
3. Update region and zone if required in `variables.tf`.
4. Run `terraform apply`
5. To delete the resources once the tutorial is finished run `terraform destroy`
