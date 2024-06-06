<div align="center">

<pre>
██████╗  ██████╗███████╗███╗   ███╗     ██   ██ 
██╔══██╗██╔════╝██╔════╝████╗ ████║    █████████
██████╔╝██║     █████╗  ██╔████╔██║    █████████
██╔══██╗██║     ██╔══╝  ██║╚██╔╝██║     ███████ 
██████╔╝╚██████╗██║     ██║ ╚═╝ ██║      █████  
╚═════╝  ╚═════╝╚═╝     ╚═╝     ╚═╝       ███   

 ██████╗ ██████╗ ███████╗███╗   ██╗    ███████╗ ██████╗ ██╗   ██╗██████╗  ██████╗███████╗
██╔═══██╗██╔══██╗██╔════╝████╗  ██║    ██╔════╝██╔═══██╗██║   ██║██╔══██╗██╔════╝██╔════╝
██║   ██║██████╔╝█████╗  ██╔██╗ ██║    ███████╗██║   ██║██║   ██║██████╔╝██║     █████╗  
██║   ██║██╔═══╝ ██╔══╝  ██║╚██╗██║    ╚════██║██║   ██║██║   ██║██╔══██╗██║     ██╔══╝  
╚██████╔╝██║     ███████╗██║ ╚████║    ███████║╚██████╔╝╚██████╔╝██║  ██║╚██████╗███████╗
 ╚═════╝ ╚═╝     ╚══════╝╚═╝  ╚═══╝    ╚══════╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝ ╚═════╝╚══════╝
</pre>

### bestcloudfor.me

**Cloud, DevOps &amp; SysOps. Built in the open.**

<sub>Premier AWS Consulting Partner&nbsp;·&nbsp;Cloud agnostic&nbsp;·&nbsp;Hybrid &amp; on-prem</sub>

</div>

---

## Who we are

We're **BCFM**, a team of cloud, DevOps and SysOps engineers. We run production for high-traffic, regulated, and growth-stage workloads on **AWS, GCP, Azure, and on-prem**. AWS is where we go deepest (Premier partner, DevOps + Migration competencies), but we are cloud agnostic by design.

This GitHub organization is where we open-source the tooling, modules and patterns we use to do that work.

```yaml
apiVersion: bestcloudfor.me/v1
kind: Organization
metadata:
  name: bcfm
  annotations:
    open-source: love
    aws-partner: premier
spec:
  works-on:
    - cloud-infrastructure
    - platform-engineering
    - automation-and-cicd
    - application-modernization
  runs-on:
    cloud: [aws, gcp, azure, oci, digitalocean, hetzner]
    on-prem: [vmware, openstack, proxmox, eks-anywhere, bare-metal]
    edge: [cloudflare, fastly]
  values:
    - ship-in-the-open
    - reliability-by-default
    - cloud-agnostic-by-design
```

## What we work in

We're tool-pragmatic: pick the right thing for the workload, then run it well.

```
$ tree -L 2 ~/bcfm/stack
.
├── clouds/
│   ├── aws · gcp · azure · oci · digitalocean · hetzner · cloudflare
│   ├── on-prem/   vmware · openstack · proxmox · kvm/libvirt · nutanix · bare-metal
│   └── edge/      cloudflare · fastly
├── containers/
│   ├── orchestration · kubernetes · nomad · helm
│   ├── runtimes ····· docker · containerd
│   └── distros ······ eks · gke · aks · eks-anywhere · rancher · openshift
├── iac/
│   └── terraform · opentofu · pulumi · cloudformation · aws-cdk · ansible · crossplane
├── ci-cd/
│   └── github-actions · gitlab-ci · jenkins · argocd · flux · tekton
├── observability/
│   ├── metrics · prometheus · grafana · mimir · datadog · new-relic
│   ├── logs ··· loki · opensearch · elk · fluent-bit
│   └── traces · tempo · jaeger · opentelemetry
├── network/
│   ├── mesh ····· istio · linkerd · cilium · consul
│   └── ingress ·· envoy · traefik · nginx · haproxy
├── data/
│   ├── relational ·· postgresql · mysql · mariadb
│   ├── document ···· mongodb · dynamodb · cassandra
│   ├── cache ······· redis · memcached
│   ├── search ······ opensearch · elasticsearch
│   ├── analytics ··· clickhouse
│   └── streaming ··· kafka · rabbitmq · nats · pulsar
├── security/
│   ├── secrets · vault · sops · cert-manager
│   ├── policy ·· opa · kyverno
│   ├── runtime · falco · trivy · wazuh
│   └── edge ···· aws-waf · shield · guardduty · cloudflare
├── platform/
│   └── backstage · crossplane · kubecost · tilt · skaffold
└── languages/
    └── go · python · typescript · bash · rust · java
```

## Open source

The repositories below are the production-grade tools we built for ourselves (Terraform modules, GitHub Actions, operators, CLIs, pipelines, runbooks) and chose to share. Some are small, some run on real workloads behind the scenes every day.

Issues, pull requests, and ideas are all welcome. First-timers especially. Look for `good first issue` and `help wanted` labels to get started.

## Talk to us

- **Open source questions**: issues and discussions on the relevant repository
- **Engineering work &amp; partnerships**: [bestcloudfor.me](https://bestcloudfor.me)

---

<div align="center">
  <sub>Built by the BCFM team. Powered by curiosity and a lot of YAML.</sub>
</div>
