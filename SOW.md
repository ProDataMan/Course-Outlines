**Statement of Work: Hardening ASPE / CPRIME AWS Account and Organizations**
---
**Project Overview:**
This project aims to enhance the security of ASPE/CPRIME's AWS Cloud Account through a phased approach involving the separation of the account into three organizations, implementation of account policies, log management, detailed usage and billing tracking, and automation of resource provisioning and decommissioning. The project also includes ongoing support for policy updates and security monitoring.

**Scope of Work:**
The scope of work for this project includes the following key phases and activities:

**Phase 1: Break Account into 3 Separate Organizations:**
- Configure ASPE/CPRIME AWS account into three separate organizations.
- Designate one organization for Account and Policy Management, another for Log Management, and a third for Lab Server Provisioning and Management.
- Implement a secure VPC structure, including a "Screening VPC" and "Shared Services VPC," to enhance defense in depth.

**Phase 2a: Setup Account Policies in Accounts Org:**
- Utilize AWS Organizations and AWS Control Tower tools to push Service Control Policies from Account and Policy Management to the Lab organization.
- Enforce access controls and restrictions to prevent unauthorized actions.

**Phase 2b: Setup Log Shipping:**
- Configure log shipping from the Account organization and Lab organization to a dedicated Monitoring organization.
- Centralize log data for effective security monitoring and incident response.

**Phase 2c: Detailed Usage and Billing Log Shipping:**
- Implement log shipping and visualization for Usage and Billing data to track resource consumption within predefined limits.
- Enable simplified tracking and management of resource usage.

**Phase 3a: Setup Provisioning Automation:**
- Develop self-service automation for provisioning lab resources, leveraging AWS CloudFormation or other provisioning tools.
- Enforce limits on EC2 provisioning based on class schedules and registered students.

**Phase 3b: Setup Decommissioning Automation:**
- Implement automation to decommission lab servers daily based on course end dates, removing servers by 6pm Eastern Time or class end time + 2 hours.

**Phase 4: Ongoing Support and Training:**
- Provide ongoing support for one year, including minor policy updates and continuous security monitoring.
- Conduct instructor/administrator training sessions, including content development, on a quarterly basis to ensure effective utilization of security measures.

**Deliverables:**
Upon completion of the project, the following deliverables will be provided:

- Detailed architectural documentation illustrating the account structure, policies, and organization setup.
- Comprehensive documentation of the implemented automation workflows, provisioning and decommissioning processes, and usage tracking.
- Training materials, including slide decks and guides, for the quarterly training sessions and instructor/administrator training.
- Ongoing support for one year, including regular communication and assistance for policy updates, security monitoring, and training.

**Timeline:**
The project is expected to be completed within [estimated timeline], considering the phased approach and specific tasks outlined.

**Budget:**
The estimated budget for this project is [project budget]. Any changes or additional costs will be communicated and agreed upon in advance.

---
