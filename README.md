git checkout 2ab0c76205d3bdb75ca24591b536747620d1df7f

terraform init
terraform apply

git checkout fdc543bc602a809868cb6ff722bf97be8e83b7f6
terraform apply

git checkout 181663bb532a88ff367d812dd339af955b2a4a21
terraform init
terraform apply

git checkout d2389c4531dc46321f1d67ea4613d0fdf1cca0b8
terraform apply

git checkout 612ef0064216c97eeaafc55c47d3a922774a578d
kubectl apply -f k8s/provisioner.yaml
