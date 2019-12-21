# kudo-minio-standalone
Demo minio operator using KUDO

Trying to learn KUDO by creating a Minio(standalone) operator. 

Requirement:
- Tested against Kubernetes 1.5.x
- Needs KUDO operator version 0.8.0

Deployment:
- Needs a PV of 10G called minio-pv
- You can use the sample pv.yaml under the folder operator/template/pv.yaml
- To install the operator
  **kubectl kudo install kudo-minio-standalone**

