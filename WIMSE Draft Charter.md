# Proposed Charter for Workload Identities in Multi-Service Environments (WIMSE) 

# Scope

The Workload Identity in Multi-Service Environments (WIMSE) working group is chartered to address the challenges associated with implementing fine-grained, least privilege access control for  workloads deployed across multiple service platforms, spanning both public and private clouds. The work will leverage existing standards, open source projects, and community practices, focusing on combining them in a coherent manner to address multi-service workload identity use cases such as those identified in the [Workload Identity Use Cases](https://datatracker.ietf.org/doc/draft-gilman-wimse-use-cases/) Internet Draft.

# Background and Motivation

The drive for business flexibility, cost-efficiency, resilience, and compliance make maintaining least privilege access for services increasingly complex. As a result of the adoption of microservice architectures, applications are composed of multiple microservices that need to authenticate to each other while making authorization decisions based on the original caller, their context, and the actions of other workloads that acted on a request. These microservices are often distributed across trust boundaries, without a single centralized controller managing the different identities or authorization policies.

While several standards and open-source projects offer foundational elements for secure service identity, there remains a lack of clarity in their interoperation and combination. These technologies have been combined in a variety of ways in practice, but the solutions have existed in relative isolation. This ambiguity can lead to inconsistencies, interoperability issues, and potential security vulnerabilities.

# Goals and Deliverables

The WIMSE working group aims to:

* Establish Best Current Practices (BCPs): Define guidelines on effectively combining existing standards from different ecosystems to cater to various workload identity scenarios.
* Identify and Advocate for Gap-filling Work: Engage with other relevant working groups to pinpoint and address gaps in current standards. This will involve thorough collaboration, ensuring that emerging standards are consistent, holistic, and interoperable.
* Standardize New Solutions: If gaps cannot be addressed within other working groups, initiate and draft new standards that provide the needed functionality and ensure their widespread adoption.

# Leadership

\[Chairs to be appointed\]

# Meeting and Communication Information

The WIMSE working group will maintain an active mailing list, host periodic virtual meetings, and hold face-to-face meetings during IETF gatherings as deemed necessary. All communications, decisions, and drafts will be archived and made accessible to the wider community.

# Dependencies and Liaisons

The WIMSE working group will closely collaborate with:

* Other IETF working groups that address topics related to identity, authentication, and authorization, including, but not limited to, OAuth, SCIM, and RATS.
* The Cloud Native Computing Foundation (CNCF), particularly with regard to the SPIFFE/SPIRE project.
* The OpenID Foundation and other organizations working on similar standards.

# Duration

The WIMSE working group is envisaged as an ongoing effort, given the evolving nature of service platforms and the continuous drive for enhanced security measures. However, periodic reviews will be conducted to reassess its relevance and objectives.
