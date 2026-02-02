# openstack-knowledge-base
- README.md
- LICENSE
- 00-introduction/
    - what-is-openstack.md
    - openstack-architecture-overview.md
    - openstack-use-cases.md
- 01-core-concepts/
│   ├── projects-and-domains.md
│   ├── users-roles-policies.md
│   ├── regions-availability-zones.md
│   └── quotas-and-allocation-ratios.md
│
├── 02-openstack-services/
│   ├── compute-nova/
│   │   ├── overview.md
│   │   ├── nova-architecture.md
│   │   └── common-cli-commands.md
│   │
│   ├── networking-neutron/
│   │   ├── overview.md
│   │   ├── neutron-components.md
│   │   ├── security-groups.md
│   │   └── common-cli-commands.md
│   │
│   ├── storage-cinder/
│   │   ├── overview.md
│   │   ├── volume-lifecycle.md
│   │   └── common-cli-commands.md
│   │
│   ├── images-glance/
│   │   ├── overview.md
│   │   └── image-vs-volume.md
│   │
│   └── identity-keystone/
│       ├── overview.md
│       ├── authentication-flow.md
│       └── roles-and-policies.md
│
├── 03-hands-on/
│   ├── environment-setup.md
│   ├── instance-lifecycle.md
│   ├── volume-based-boot.md
│   ├── networking-examples.md
│   └── common-troubleshooting.md
│
├── 04-architecture-and-design/
│   ├── single-region-design.md
│   ├── multi-region-design.md
│   ├── ha-and-scalability.md
│   └── enterprise-design-patterns.md
│
├── 05-security/
│   ├── openstack-security-model.md
│   ├── keystone-hardening.md
│   ├── neutron-security.md
│   └── best-practices.md
│
├── 06-operations/
│   ├── monitoring-and-logging.md
│   ├── capacity-planning.md
│   ├── backup-and-recovery.md
│   └── upgrades-and-maintenance.md
│
├── 07-api-and-internals/
│   ├── rest-apis.md
│   ├── service-catalog.md
│   └── token-workflows.md
│
├── 08-real-world-notes/
│   ├── common-mistakes.md
│   ├── performance-lessons.md
│   └── production-gotchas.md
│
└── assets/
    ├── images/
    └── diagrams/
