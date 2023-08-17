# Software/Cloud Engineering

[![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)](https://www.gnu.org/software/gnu-c-manual/gnu-c-manual.html)
[![TypeScript](https://img.shields.io/badge/ts-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/docs/)
[![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/doc/)
[![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/docs/home/)
[![Google Cloud](https://img.shields.io/badge/GCP-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/docs?hl=fr)
[![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)](https://developer.hashicorp.com/terraform)
[![Ansible](https://img.shields.io/badge/ansible-%23cc0607.svg?style=for-the-badge&logo=ansible&logoColor=white)](https://docs.ansible.com/)
[![Rocky Linux](https://img.shields.io/badge/RL-%2310B981?style=for-the-badge&logo=rockylinux&logoColor=white)](https://docs.rockylinux.org/)

Hi! I'm a French native interested in distributed/edge computing, zero-trust network and general automation.

I'm working on system and software design, infrastructure provisioning, configuration management, cloud and database migrations, GraphQL ecosystem, Kubernetes environment... I'm coding with Go and Typescript. I put my best efforts to ensure automation and reduce toil at each system level to provide flawless, maintainable and cost-efficient solutions.

## Skills

### [🌴 3D web application with React and Blender](https://github.com/gmarcha/vite-app)

Leverage 3D UX/UI into web applications with node ecosystem and edge technologies.

<p align="center">
	<a href="https://github.com/gmarcha/vite-app"><img src="https://raw.githubusercontent.com/gmarcha/vite-app/master/.github/assets/screenshot-230813024108.png" width="600"></a>
</p>

### [☁️ Infrastructure as Code with Google Cloud, Terraform and Kubernetes](https://github.com/gmarcha/landing-deploy)

Deploy Google Cloud resources with Terraform, Ansible and self-deployed Kubernetes following GitOps practices.

<p align="center">
	<a href="https://github.com/gmarcha/landing-deploy"><img src="https://raw.githubusercontent.com/gmarcha/landing-deploy/master/.github/assets/gcp-vm.png" width="600"></a>
</p>

### [🗃️ Application management with Kubernetes and Helm](https://github.com/gmarcha/hasura-chart)

Package a Hasura application into a Kubernetes Helm chart and deploy Helm repository as a static website.

<p align="center">
	<a href="https://github.com/gmarcha/hasura-chart"><img src="https://raw.githubusercontent.com/gmarcha/hasura-chart/master/.github/assets/kubernetes-resources.png" width="600"></a>
</p>

## Experiences

During last years, I highly focused on Google Cloud provisioning, K3s deployments and GitOps practices through [Flux](https://fluxcd.io/) and [Argo](https://argoproj.github.io/) with the aim to provide reliable, scalable and secure systems. That leads me to investigate in multi-cloud and hybrid scenarios for deploying Kubernetes. [K3s](https://k3s.io/) and [Rancher](https://ranchermanager.docs.rancher.com/getting-started/overview) offers the ability to embrace this kind of scenarios, allowing to deploy control-plane clusters, regional clusters and edge clusters in any desired configuration. I gained good knowledge about network and load balancing issues in distributed systems, from a cloud-hosted or on-premise perspectives. [K0s](https://k0sproject.io/) from Google teams is a good alternative for ready-to-use clusters. For managing multi-cluster infrastructure, there are basically three ecosystems with different level of integration and flexibility: entreprise-grade [OpenShift Container Platform](https://docs.okd.io/latest/installing/index.html) (and OpenShift Platform Plus for multi-cluster control plane) which provides user-provisioned or installer-provisioned installation, open-source [Kubesphere Platform](https://www.kubesphere.io/projects/) based on a full open source stack from observability to continuous integration, the Rancher suite for hybrid-orchestration and flexible scenarios (helped by [Karmada](https://karmada.io/docs/tutorials/autoscaling-with-federatedhpa) cluster federation capabilities, Harvester integration for legacy virtual machine workloads or other external control plane tools). [Nomad](https://www.nomadproject.io/) is an alternative and interesting approach for entreprise-grade hybrid-orchestration.

I also investigated authn/authz solutions and became an [Ory.sh](https://www.ory.sh/) user. Compared to keycloak monolithic approach and SSO based on OIDC, Ory is an open source cloud-hosted and headless solution based on a micro-service architecture, each service implementing a precise requirement in a lightweight manner. It is possible to deploy each service (Kratos, Hydra, Oathkeeper, Keto) independently and in a self-hosted fashion. Ory Kratos is an IAM server which integrates with external OIDC providers while Ory Hydra is an OAuth2 server which allows to become an OIDC provider. This micro-service architecture grants so much flexibility to implement multi-tenancy requirements (single server with single database, multiple servers with single database, multiple servers with multiple databases) and to leverage a DevOps approach even for critical operations as authentication and authorization. I would really enjoy to collaborate on an open source RBAC implementation for Ory Keto, using operator pattern for example (see [example](https://docs.mojaloop.io/business-operations-framework-docs/guide/SecurityBC.html)).

I did a lot in CRUD generation from database schemas in OpenAPI ecosystem and then in GraphQL ecosystem, extensively using tools such as [Hasura](https://hasura.io/) or [Graphql-mesh](https://the-guild.dev/graphql/mesh). Thus I'm mostly using Postgres because of its rich ecosystem, its fined grained authorization system with RLS feature and its "easy" migration usage for legacy SQL databases.

Finally I like to design and create user interfaces or 3D experiences to drive my ideas forward, using edge technology to build intuitive and captivating applications.

## Other projects

- [Webserv](https://github.com/c3b5aw/webserv), a HTTP/1.1 C++ server implementation made in pair working with awesome [@c3b5aw](https://github.com/c3b5aw). Support for basic nginx configuration files, event-driven I/O handling, and multiple data response formats (urlencoded, multipart and transfer-encoding chunk mode).
- [PipexMedic](https://github.com/gmarcha/pipexMedic), a C functional tester for a unix system programming project, Pipex. Intensive process creation, low-level inter-process communication, I/O redirection, signal handling. 
- [SoLong](https://github.com/gmarcha/so-long), a 2D game written in C with a X11 library. Implementing an application loop, event handling, frame building and rendering.

## Technologies

[![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)](https://www.gnu.org/software/gnu-c-manual/gnu-c-manual.html)
[![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/doc/)
[![TypeScript](https://img.shields.io/badge/ts-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/docs/)
[![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)](https://graphql.org/learn/)
[![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/docs/home/)
[![Helm](https://img.shields.io/badge/helm-%23267a9e.svg?style=for-the-badge&logo=helm&logoColor=white)](https://helm.sh/docs/)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://docs.docker.com/engine/reference/builder/)
[![Google Cloud](https://img.shields.io/badge/GCP-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/docs?hl=fr)
[![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://docs.aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)](https://developer.hashicorp.com/terraform)
[![Pulumi](https://img.shields.io/badge/pulumi-%231A1918.svg?style=for-the-badge&logo=pulumi&logoColor=white)](https://www.pulumi.com/docs/)
[![Ansible](https://img.shields.io/badge/ansible-%23cc0607.svg?style=for-the-badge&logo=ansible&logoColor=white)](https://docs.ansible.com/)
[![Vagrant](https://img.shields.io/badge/vagrant-%231563FF.svg?style=for-the-badge&logo=vagrant&logoColor=white)](https://developer.hashicorp.com/vagrant/docs)
[![Packer](https://img.shields.io/badge/packer-%2301a8ef.svg?style=for-the-badge&logo=packer&logoColor=white)](https://developer.hashicorp.com/packer/docs)
[![Rocky Linux](https://img.shields.io/badge/RL-%2310B981?style=for-the-badge&logo=rockylinux&logoColor=white)](https://docs.rockylinux.org/)

[![FluxCD](https://img.shields.io/badge/FluxCD-%23316ce4.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://fluxcd.io/flux/)
[![ArgoCD](https://img.shields.io/badge/ArgoCD-%23ff733e.svg?style=for-the-badge&logo=argo&logoColor=white)](https://argo-cd.readthedocs.io/en/stable/)
[![Karmada](https://img.shields.io/badge/karmada-%232665fe.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://karmada.io/docs/)
[![K3s](https://img.shields.io/badge/k3s-%23323330.svg?style=for-the-badge&logo=k3s&logoColor=%23ffc71c)](https://docs.k3s.io/)
[![Rancher](https://img.shields.io/badge/rancher-%230075A8.svg?style=for-the-badge&logo=rancher&logoColor=white)](https://ranchermanager.docs.rancher.com/)
[![Harvester](https://img.shields.io/badge/harvester-%2300a384.svg?style=for-the-badge&logo=rancher&logoColor=white)](https://docs.harvesterhci.io/v1.1)
[![Longhorn](https://img.shields.io/badge/longhorn-%235f224b.svg?style=for-the-badge&logo=rancher&logoColor=white)](https://longhorn.io/docs/1.5.1/)
[![KubeVirt](https://img.shields.io/badge/kubevirt-%2300aab2.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubevirt.io/user-guide/)
[![KubeSphere](https://img.shields.io/badge/kubesphere-%2351b484.svg?style=for-the-badge&logo=kubernetes&logoColor=white)](https://www.kubesphere.io/docs/v3.3/)
[![OpenShift](https://img.shields.io/badge/openshift-%23db212e.svg?style=for-the-badge&logo=redhatopenshift&logoColor=white)](https://docs.okd.io/latest/welcome/index.html)
[![Vault](https://img.shields.io/badge/vault-%23323330.svg?style=for-the-badge&logo=vault&logoColor=%23fed813)](https://developer.hashicorp.com/vault/docs)

[![GitHub](https://img.shields.io/badge/github_actions-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://docs.github.com/fr/actions)
[![GitLab](https://img.shields.io/badge/gitlab_CI-%23fc6e26.svg?style=for-the-badge&logo=gitlab&logoColor=white)](https://docs.gitlab.com/ee/ci/)
[![CircleCI](https://img.shields.io/badge/circle%20ci-%23343432.svg?style=for-the-badge&logo=circleci&logoColor=white)](https://circleci.com/docs/)
[![Dagger](https://img.shields.io/badge/dagger-%230e2b3d.svg?style=for-the-badge&logo=docker&logoColor=white)](https://docs.dagger.io/)
[![Jenkins](https://img.shields.io/badge/jenkins-%23335060.svg?style=for-the-badge&logo=jenkins&logoColor=white)](https://www.jenkins.io/doc/book/)
[![Node-RED](https://img.shields.io/badge/Node--RED-%238F0000.svg?style=for-the-badge&logo=node-red&logoColor=white)](https://nodered.org/docs/)
[![n8n](https://img.shields.io/badge/n8n-%23eb4b71.svg?style=for-the-badge)](https://docs.n8n.io/#)

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
[![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)](https://developers.notion.com/)
[![Miro](https://img.shields.io/badge/miro-%23050038.svg?style=for-the-badge&logo=miro&logoColor=%23ffd02e)](https://miro.com/templates/documentation/)
[![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)](https://help.figma.com/hc/fr)
[![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)](https://confluence.atlassian.com/jira)
