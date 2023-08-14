# Software/Cloud Engineering

Hi! I'm a French native interested in distributed/edge computing, zero-trust network and general automation.

I'm working on system and software design, infrastructure provisioning, configuration management, cloud and database migrations, GraphQL ecosystem, Kubernetes environment... I'm coding with Go and Typescript. I put my best efforts to ensure automation and reduce toil at each system level to provide flawless, maintainable and cost-efficient solutions.

During last years, I highly focused on Google Cloud provisioning, K3s deployments and GitOps practices through [Flux](https://fluxcd.io/) and [Argo](https://argoproj.github.io/) with the aim to provide reliable, scalable and secure systems. That leads me to investigate in multi-cloud and hybrid scenarios for deploying Kubernetes. [K3s](https://k3s.io/) offers the ability to embrace this kind of scenarios, allowing to deploy control-plane clusters, regional clusters and edge clusters in any desired configuration. I gained good knowledge about network and load balancing issues in distributed systems, from a cloud-hosted or on-premise perspectives. [K0s](https://k0sproject.io/) from Google teams is a good alternative for ready-to-use clusters. For managing multi-cluster infrastructure, there are basically three ecosystems with different level of integration and flexibility: entreprise-grade OpenShift Container Platform (and OpenShift Platform Plus for multi-cluster control plane) which provides user-provisioned or installer-provisioned [installation](https://docs.okd.io/latest/installing/index.html), open-source Kubesphere Platform based on a full open source [stack](https://www.kubesphere.io/projects/) from observability to continuous integration, the Rancher suite for hybrid-orchestration and flexible scenarios (helped by Karmada cluster federation [capabilities](https://karmada.io/docs/tutorials/autoscaling-with-federatedhpa), Harvester integration for legacy virtual machine workloads or other external control plane tools). Nomad is an alternative and interesting approach for entreprise-grade [hybrid-orchestration](https://www.nomadproject.io/).

I also investigated authn/authz solutions and became an [Ory.sh](https://www.ory.sh/) user. Compared to keycloak monolithic approach and SSO based on OIDC, Ory is an open source cloud-hosted and headless solution based on a micro-service architecture, each service implementing a precise requirement in a lightweight manner. It is possible to deploy each service (Kratos, Hydra, Oathkeeper, Keto) independently and in a self-hosted fashion. This micro-service architecture grants so much flexibility to implement multi-tenancy requirements (single server with single database, multiple servers with single database, multiple servers with multiple databases) and to leverage a DevOps approach even for critical operations as authentication and authorization. I would really enjoy to collaborate on an open source RBAC implementation for Ory Keto, using operator pattern for example (see [example](https://docs.mojaloop.io/business-operations-framework-docs/guide/SecurityBC.html)).

I did a lot in CRUD generation from database schemas in OpenAPI ecosystem and then in GraphQL ecosystem, extensively using tools such as [Postgraphile](https://www.graphile.org/postgraphile/), [Graphql-mesh]() or [Hasura](). Thus I'm mostly using Postgres because of its rich ecosystem, its fined grained authorization system with RLS feature and its "easy" migration usage for legacy SQL databases. Finally I like to design and create user interfaces or 3D experiences to drive my ideas forward, using edge technology to build intuitive and captivating applications.

## Technologies

[![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)](https://www.gnu.org/software/gnu-c-manual/gnu-c-manual.html)
[![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/doc/)
[![JavaScript](https://img.shields.io/badge/js-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TypeScript](https://img.shields.io/badge/ts-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/docs/)
[![NodeJS](https://img.shields.io/badge/node-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/en/docs)
[![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)](https://graphql.org/learn/)
[![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/docs/home/)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://docs.docker.com/engine/reference/builder/)
[![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://docs.aws.amazon.com/)
[![Google Cloud](https://img.shields.io/badge/GCP-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/docs?hl=fr)
[![Scaleway](https://img.shields.io/badge/scaleway-%234f0599.svg?style=for-the-badge&logo=scaleway&logoColor=white)](https://www.scaleway.com/en/docs/)
[![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)](https://developer.hashicorp.com/terraform)
[![Pulumi](https://img.shields.io/badge/pulumi-%231A1918.svg?style=for-the-badge&logo=pulumi&logoColor=white)](https://www.pulumi.com/docs/)
[![Ansible](https://img.shields.io/badge/ansible-%23cc0607.svg?style=for-the-badge&logo=ansible&logoColor=white)](https://docs.ansible.com/)
[![Vagrant](https://img.shields.io/badge/vagrant-%231563FF.svg?style=for-the-badge&logo=vagrant&logoColor=white)](https://developer.hashicorp.com/vagrant/docs)
[![Packer](https://img.shields.io/badge/packer-%2301a8ef.svg?style=for-the-badge&logo=packer&logoColor=white)](https://developer.hashicorp.com/packer/docs)
[![Rocky Linux](https://img.shields.io/badge/RL-%2310B981?style=for-the-badge&logo=rockylinux&logoColor=white)](https://docs.rockylinux.org/)

[![FluxCD](https://img.shields.io/badge/FluxCD-%23316ce4.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://fluxcd.io/flux/)
[![ArgoCD](https://img.shields.io/badge/ArgoCD-%23ff733e.svg?style=for-the-badge&logo=argo&logoColor=white)](https://argo-cd.readthedocs.io/en/stable/)
[![Karmada](https://img.shields.io/badge/karmada-%232665fe.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://karmada.io/docs/)
[![Rancher](https://img.shields.io/badge/rancher-%230075A8.svg?style=for-the-badge&logo=rancher&logoColor=white)](https://ranchermanager.docs.rancher.com/)
[![K3s](https://img.shields.io/badge/k3s-%23323330.svg?style=for-the-badge&logo=k3s&logoColor=%23ffc71c)](https://docs.k3s.io/)
[![Harvester](https://img.shields.io/badge/harvester-%2300a384.svg?style=for-the-badge&logo=rancher&logoColor=white)](https://docs.harvesterhci.io/v1.1)
[![Longhorn](https://img.shields.io/badge/longhorn-%235f224b.svg?style=for-the-badge&logo=rancher&logoColor=white)](https://longhorn.io/docs/1.5.1/)
[![KubeVirt](https://img.shields.io/badge/kubevirt-%2300aab2.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubevirt.io/user-guide/)
[![KubeSphere](https://img.shields.io/badge/KubeSphere-%2351b484.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://www.kubesphere.io/docs/v3.3/)

[![GitHub](https://img.shields.io/badge/github_actions-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://docs.github.com/fr/actions)
[![GitLab](https://img.shields.io/badge/gitlab_CI-%23fc6e26.svg?style=for-the-badge&logo=gitlab&logoColor=white)](https://docs.gitlab.com/ee/ci/)
[![CircleCI](https://img.shields.io/badge/circle%20ci-%23343432.svg?style=for-the-badge&logo=circleci&logoColor=white)](https://circleci.com/docs/)
[![Dagger](https://img.shields.io/badge/dagger-%230e2b3d.svg?style=for-the-badge&logo=docker&logoColor=white)](https://docs.dagger.io/)
[![Jenkins](https://img.shields.io/badge/jenkins-%23335060.svg?style=for-the-badge&logo=jenkins&logoColor=white)](https://www.jenkins.io/doc/book/)
[![Node-RED](https://img.shields.io/badge/Node--RED-%238F0000.svg?style=for-the-badge&logo=node-red&logoColor=white)](https://nodered.org/docs/)
[![n8n](https://img.shields.io/badge/n8n-%23eb4b71.svg?style=for-the-badge)](https://docs.n8n.io/#)
[![Vault](https://img.shields.io/badge/vault-%23323330.svg?style=for-the-badge&logo=vault&logoColor=%23fed813)](https://developer.hashicorp.com/vault/docs)

[![Ory.sh](https://img.shields.io/badge/Ory-%235528ff.svg?style=for-the-badge&logo=sourcehut&logoColor=white)](https://www.ory.sh/docs/ecosystem/projects)
[![Apollo-GraphQL](https://img.shields.io/badge/-Apollo-311C87?style=for-the-badge&logo=apollo-graphql&logoColor=white)](https://www.apollographql.com/docs/)
[![Hasura](https://img.shields.io/badge/Hasura-%231eb5d4.svg?style=for-the-badge&logo=graphql&logoColor=white)](https://hasura.io/docs/latest/index/)
[![GraphQL Mesh](https://img.shields.io/badge/GraphQL--Mesh-%231A1918.svg?style=for-the-badge&logo=graphql&logoColor=white)](https://the-guild.dev/graphql/mesh/docs)
[![Postgraphile](https://img.shields.io/badge/postgraphile-%234ba8ff.svg?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.graphile.org/postgraphile/introduction/)
[![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/docs/current/index.html)
[![ApacheCassandra](https://img.shields.io/badge/cassandra-%231287B1.svg?style=for-the-badge&logo=apache-cassandra&logoColor=white)](https://cassandra.apache.org/doc/latest/)
[![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io/docs/)

[![React](https://img.shields.io/badge/react-%23323330.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev/learn)
[![Mantine](https://img.shields.io/badge/mantine-%23349aef.svg?style=for-the-badge&logo=react&logoColor=white)](https://mantine.dev/pages/getting-started/)
[![Emotion](https://img.shields.io/badge/emotion-%23d26ac1.svg?style=for-the-badge&logo=jss&logoColor=white)](https://emotion.sh/docs/introduction)
[![Tailwind](https://img.shields.io/badge/tailwind-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/docs/installation)
[![Next JS](https://img.shields.io/badge/Next-%231A1918.svg?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/docs)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/docs)
[![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white)](https://docs.blender.org/manual/en/latest/)

[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/developers/docs/intro)
[![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)](https://help.figma.com/hc/fr)
[![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)](https://confluence.atlassian.com/jira)
[![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)](https://developers.notion.com/)
