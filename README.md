# Cloud-Native Case Study

### Overview
```
Contoso is a leading retail e-commerce company for families in Europe, with plans to accelerate the 
development of new products and services worldwide. “Our technology platform must be a business enabler. 
That starts by removing limiting factors,” said the Director of Architecture & Technology. 
```

### Existing Environment
```
- 25 backend microservices for the company's mobile apps hosted on standalone Linux virtual machines

- 3 SQL servers hosted on Windows virtual machines

- 1 IBM application gateway

- It took up to 2 weeks to provision a new infrastructure environment as the entire process was manual 
and based on demand approvals
```


### Planned Changes
```
1. After a few months of experimentation, the platform team decided to use Kubernetes as its orchestration platform for existing microservices. 

2. Shift focus from provisioning and configuring infrastructure environments to building services.

3. The company required complementary technologies to handle non-functional requirements such as automated deployments, 
security, monitoring, and recovery.

4. The choices of technology matched the cloud-native and multi-cloud requirements essential to the transformation 
of application delivery.
```

### Technical Requirements
```
Contoso must meet the following technical requirements:

1. Packaging of microservices and its related artifacts must be standardized.
2. Application logs and service metrics must be retained based on the agreed retention policy.
3. Administrative effort and costs must be minimized whenever possible.
4. The principle of least privilege must be used.
```

#### Question # 1 (Multiple Choice)
Answer the following question based on the information presented in the case study.
```
Which of the below tools must be implemented for the planned change #2?

A. Ansible
B. Helm
C. Terraform
D. Both A and C
E. Both B and C
```
#### Question # 2 (Multiple Choice)
Answer the following question based on the information presented in the case study.
```
You need to implement the technical requirement #1.
What should you do?

A. Build CI/CD pipelines using YAML
B. Use Helm
C. Use Docker Compose
D. None of the above
```

#### Question # 3 (Multiple Choice)
Answer the following question based on the information presented in the case study.
```
You need to implement the technical requirement #2.
What should you do?

A. Implement Prometheus/Grafana
B. Implement the ELK stack
C. Both A and B
D. Only B
```

#### Question # 4 (Multiple Choice)
Answer the following question based on the information presented in the case study.
```
What can be done to implement Technical requirement #3 in context of SQL VMs?

A. Consolidate the three SQL servers into one
B. Migrate the SQL databases from VMs into managed SQL PaaS
C. Migrate to Oracke Databases
D. None of the above
```

#### Question # 5 (Multiple Choice)
Answer the following question based on the information presented in the case study.
```
As the number of microservices grew from 25 to 85 in the last one year, Contoso faced challenges like 
service routing, end-end service observability ans security.

What should you do?

A. Implement the elastic stack for observability
B. Use Kubernetes service discovery
C. Implement a service-mesh like Istio
D. None of the above
```

#### Question # 6 (Multiple Choice)
Answer the following question based on the information presented in the case study.
```
You need to implement the technical requirement #4 in the kubernetes cluster.
What should you do?

A. Use resource requests and limits
B. Use K8s namespaces with IAM rules
C. Limit access to kubernetes control plane from management VMs
D. Both B and C
```


