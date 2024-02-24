Terraform notes
1) Terraform is an Infrastructure as Code (IaC) tool that enables you to define and provision infrastructure using declarative configuration files.

2) It uses a domain-specific language (DSL) called HashiCorp Configuration Language (HCL) to define infrastructure components and their relationships.

3) Terraform operates through a cycle of planning, applying, and destroying infrastructure. Planning involves generating an execution plan based on the configuration, applying involves executing that plan to create or modify infrastructure, and destroying involves removing the infrastructure provisioned by Terraform.

4) Providers in Terraform are responsible for interacting with APIs of various cloud providers or other infrastructure services. Each provider offers resources that can be managed by Terraform.

5) Terraform state files store information about the infrastructure managed by Terraform. These state files are crucial for tracking the current state of resources and managing changes.

6) Modules in Terraform allow you to encapsulate and reuse configuration. They help in organizing and abstracting infrastructure components for easier management and reuse across different projects.