# Capstone-Project-2--Setting-Up-a-Peering-Connection



**Setting Up a Peering Connection Between Two VPCs with All Subnets in VPC_2 Accessible**

**Problem Statement:**

Organizations often need to establish communication between Amazon Virtual Private Clouds (VPCs) to enable secure and controlled data exchange. This project addresses the challenge of setting up a peering connection between two VPCs where all subnets in VPC_2 should be accessible from VPC_1. The specific problem is to create a secure and efficient VPC peering configuration that allows for seamless communication between VPCs while maintaining security and isolation. The consequences of not addressing this problem include limited inter-VPC communication, increased network complexity, and potential data transfer inefficiencies.

**Objectives:**

- Establish a VPC peering connection between VPC_1 and VPC_2.
- Ensure that all subnets in VPC_2 are accessible from VPC_1.
- Implement security controls to restrict access to the necessary resources only.
- Document the peering configuration for future reference.

**Your focus in this project should be on the following:**

- AWS VPC peering concepts and limitations.
- Network routing and security groups.
- Subnet configurations in both VPCs.
- AWS Identity and Access Management (IAM) for peering permissions.

**Deliverables**

- Successfully established VPC peering connection.
- Documentation of the peering configuration, including route tables and security group rules.
- Testing and verification report.
- Recommendations for optimizing the peering connection.

**Tasks/Activities List**

- Research AWS VPC peering and its requirements.
- Plan the peering connection, considering the network architecture and security requirements.
- Create the peering connection between VPC_1 and VPC_2.
- Configure the route tables to allow traffic between the VPCs.
- Implement security group rules to restrict access to necessary resources.
- Test the peering connection and security rules.
- Optimize the peering configuration for performance and cost-efficiency.
- Document the peering setup and configurations.

**Success Metrics**

- Successfully established VPC peering connection with all subnets in VPC_2 accessible from VPC_1.
- Traffic routing through the peering connection without issues.
- Security controls effectively restrict access to the necessary resources only.
- No data leakage between VPCs.
- Documentation for future reference and troubleshooting. 

**Bonus Points**

- Implement network monitoring and alerting for the peering connection.
- Explore AWS Transit Gateway for more advanced VPC connectivity.
- Implement advanced security controls such as Network ACLs.
- Optimize the network for low-latency communication.

**Submission Process**

- The learner should showcase their completion of the project by providing documentation of each deliverable, a live demonstration of inter-VPC communication, and a report summarizing the project's success and any potential optimizations made. The presentation should include an overview of the challenges faced and how they were overcome during the peering setup and configuration.
