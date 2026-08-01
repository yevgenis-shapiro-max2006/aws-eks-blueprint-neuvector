<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/de4ece14-4524-4da8-9d46-faa1ca28d59a" />



## AWS | EKS NeuVector 
NeuVector is an open-source, Kubernetes-native container security platform maintained by SUSE. It provides end-to-end security across the container lifecycle, from image scanning in CI/CD to runtime protection in production.


🎯 Architecture Overview
```
✅ VPC containing , Public+Private Subnets , NAT Gateway
✅ EKS Cluster Provisioner Workflow 
✅ MArgo Events
✅ Minio Object Storage
✅ Neuvector
```


🧱 Features
```
✔ Fully automated provisioning with Terraform
✔ High availability using multiple subnets in different Availability Zones
✔ Secure connectivity between Application and RDS
✔ Configurable environment variables for database credentials
✔ Easy to extend for other JSON data source
```



🚀 Deployment Options
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```

