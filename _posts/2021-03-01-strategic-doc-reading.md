---
layout: post
title: Strategic Doc Reading
---
Context:  


Ever since I read [this Post](https://acloudguru.com/blog/engineering/the-career-changing-art-of-reading-the-docs) I have been wanting to put that technique to good use.

With a bit of self-reflection, I believe I am the perfect candidate to test it because:
- That technique seemed like the typical one that doesn't work for regular people
- I am pretty proud of my will power, and this would put it to a test
- I tend to forget stuff that I learnt months ago, and it frustrates me a lot

So... here is my current list (and the reading time needed for each topic):
- [AWS VPC](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
  - [How it works](https://docs.aws.amazon.com/vpc/latest/userguide/how-it-works.html) - 12 mins
  - [VPC Peering](https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html) - 2 mins
    - [Basics](https://docs.aws.amazon.com/vpc/latest/peering/vpc-peering-basics.html) - 13 mins
    - [Modify](https://docs.aws.amazon.com/vpc/latest/peering/modify-peering-connections.html) - 2 mins
- [AWS RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
  - [Best Practices](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_BestPractices.html) - 23 mins for MySQL and PostgreSQL
  - [Common DBA Tasks](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Appendix.MySQL.CommonDBATasks.html) - 15 mins
  - [Advanced Aurora Auditing](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/AuroraMySQL.Auditing.html) - 7 mins
- [AWS EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) - 4 mins
  -  [Security best practices](https://docs.aws.amazon.com/eks/latest/userguide/best-practices-security.html) - 6 mins
  - [IAM and ServiceAccounts](https://docs.aws.amazon.com/eks/latest/userguide/iam-roles-for-service-accounts.html) - 2 mins
    - [OIDC provider](https://docs.aws.amazon.com/eks/latest/userguide/enable-iam-roles-for-service-accounts.html) - 2 mins
    - [Create IAM role and policy](https://docs.aws.amazon.com/eks/latest/userguide/create-service-account-iam-policy-and-role.html) - 4 mins
    - [Associate an IAM role to a service account](https://docs.aws.amazon.com/eks/latest/userguide/specify-service-account-role.html) - 5 mins
- [AWS App Mesh](https://docs.aws.amazon.com/app-mesh/latest/userguide/what-is-app-mesh.html) - 7 mins
  - [Best practices](https://docs.aws.amazon.com/app-mesh/latest/userguide/best-practices.html) - 9 mins
- [K8S](https://kubernetes.io/docs/home/)
  - [Components](https://kubernetes.io/docs/concepts/overview/components/) - 9 mins
  - [API](https://kubernetes.io/docs/concepts/overview/kubernetes-api/) - 3 mins
  - Architecture
    - [Nodes](https://kubernetes.io/docs/concepts/architecture/nodes/) - 21 mins
    - [Control plane <-> node comms](https://kubernetes.io/docs/concepts/architecture/control-plane-node-communication/)
    - [Controllers](https://kubernetes.io/docs/concepts/architecture/controller/)
    - [Cloud controller manager](https://kubernetes.io/docs/concepts/architecture/cloud-controller/)
  - [Well Known labels, annotations and taints](https://kubernetes.io/docs/reference/labels-annotations-taints/) - 8 mins

I continue adding details as I progress, but mostly these are the premises for this system to work (in order of importance):
- Do it regularly (starting with once a week, 1.5hrs.)
- Read the same docs again and again
- Prepare the next reading session in advance
- Balance between having too many docs to read and reading relevant docs. Expect constant corrections to the list because of this.


