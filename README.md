Set up ROSA cluster

Install following operators

1. RHOAI
2. NVIDIA GPU Operator
   1. https://docs.nvidia.com/datacenter/cloud-native/openshift/latest/install-gpu-ocp.html
3. Node Feature Discovery Operator
4. Service Mesh

Create DSC. Enable all the things.

```bash
oc apply -f setup/dsc.yaml
```

Go to route.
Create Data Science Project
Create workbench
