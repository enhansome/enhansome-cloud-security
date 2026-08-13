<br/>
<div align="center">

A curated list of awesome cloud security related resources.

</div>
<br/>

# Awesome Cloud Security with stars

🛡️ Awesome Cloud Security Resources ⚔️

# Contents

* [Standards](#standards)
* [Tools](#tools)
* [Reading materials](#reading-materials)
* [Free Courses](#free-courses)
* [Paid Courses](#paid-courses)
* [Bootcamps](#bootcamps)
* [Trainings](#trainings)
* [Certifications](#certifications)
* [Resource](#resource)
* [Contributing](#contributing)

# Standards

* [Compliances](#compliances)
* [Benchmarks](#benchmarks)

## Compliances

* [CSA STAR](https://cloudsecurityalliance.org/star/)
* [ISO/IEC 27017:2015](https://www.iso.org/standard/43757.html)
* [ISO/IEC 27018:2019](https://www.iso.org/standard/76559.html)
* [MTCS SS 584](https://www.imda.gov.sg/regulations-and-licensing-listing/ict-standards-and-quality-of-service/IT-Standards-and-Frameworks/ComplianceAndCertification)

## Benchmarks

* [CIS Benchmark](https://www.cisecurity.org/cis-benchmarks/)

# Tools

* [Infrastructure](#infrastructure)
* [Container](#container)
* [SaaS](#saas)
* [Penetration testing/learning](#penetration-testinglearning)
* [Native tools](#nativetools)

## Infrastructure

* [Prowler](https://github.com/toniblyx/prowler) ⭐ 14,581 | 🐛 262 | 🌐 Python | 📅 2026-08-13: Command line tool for AWS Security Best Practices Assessment, Auditing, Hardening and Forensics Readiness Tool.
* [aws-vault](https://github.com/99designs/aws-vault) ⭐ 8,980 | 🐛 1 | 🌐 Go | 📅 2025-12-30: A vault for securely storing and accessing AWS credentials in development environments.
* [checkov](https://github.com/bridgecrewio/checkov) ⭐ 8,936 | 🐛 160 | 🌐 Python | 📅 2026-08-13: A static code analysis tool for infrastructure-as-code.
* [Steampipe](https://github.com/turbot/steampipe) ⭐ 7,911 | 🐛 21 | 🌐 Go | 📅 2026-08-10: A Postgres FDW that maps APIs to SQL, plus suites of [API plugins](https://hub.steampipe.io/plugins) and [compliance mods](https://hub.steampipe.io/mods) for AWS/Azure/GCP and many others.
* [ScoutSuite](https://github.com/nccgroup/ScoutSuite) ⭐ 7,788 | 🐛 295 | 🌐 Python | 📅 2025-09-23: Multi-cloud security auditing tool.
* [tfsec](https://github.com/liamg/tfsec) ⭐ 7,026 | 🐛 18 | 🌐 Go | 📅 2026-03-25: Static analysis powered security scanner for Terraform code.
* [CloudQuery](https://github.com/cloudquery/cloudquery) ⭐ 6,482 | 🐛 164 | 🌐 Go | 📅 2026-08-13: Open source cloud asset inventory with set of pre-baked SQL [policies](https://hub.cloudquery.io/policies) for security and compliance.
* [Cloudmapper](https://github.com/duo-labs/cloudmapper) ⭐ 6,288 | 🐛 210 | 🌐 JavaScript | 📅 2024-07-15: Analyze your AWS environments.
* [Cloud-custodian](https://github.com/cloud-custodian/cloud-custodian) ⭐ 6,044 | 🐛 1,720 | 🌐 Python | 📅 2026-08-13: Rules engine for cloud security, cost optimization, and governance.
* [Deepfence ThreatMapper](https://github.com/deepfence/ThreatMapper) ⭐ 5,310 | 🐛 144 | 🌐 TypeScript | 📅 2026-06-01: Apache v2, powerful runtime vulnerability scanner for kubernetes, virtual machines and serverless.
* [pacu](https://github.com/RhinoSecurityLabs/pacu) ⭐ 5,304 | 🐛 37 | 🌐 Python | 📅 2026-05-19: The AWS exploitation framework.
* [Terrascan](https://github.com/accurics/terrascan) ⚠️ Archived: Detect compliance and security violations across Infrastructure as Code to mitigate risk before provisioning cloud native infrastructure.
* [Security Monkey](https://github.com/Netflix/security_monkey) ⚠️ Archived: Monitors AWS, GCP, OpenStack, and GitHub orgs for assets and their changes over time.
* [Cloudsploit](https://github.com/aquasecurity/cloudsploit) ⭐ 3,764 | 🐛 211 | 🌐 JavaScript | 📅 2026-07-28: Cloud security configuration checks.
* [consoleme](https://github.com/Netflix/consoleme) ⚠️ Archived: A Central Control Plane for AWS Permissions and Access
* [kics](https://github.com/Checkmarx/kics) ⭐ 2,685 | 🐛 325 | 🌐 Open Policy Agent | 📅 2026-08-13: Find security vulnerabilities, compliance issues, and infrastructure misconfigurations early in the development cycle of your infrastructure-as-code.
* [Matano](https://github.com/matanolabs/matano) ⭐ 1,693 | 🐛 55 | 🌐 Rust | 📅 2025-01-08: Open source serverless security lake platform on AWS that lets you ingest, store, and analyze data into an Apache Iceberg data lake and run realtime Python detections as code.
* [PMapper](https://github.com/nccgroup/PMapper) ⭐ 1,574 | 🐛 36 | 🌐 Python | 📅 2024-08-02: A tool for quickly evaluating IAM permissions in AWS.
* [pacbot](https://github.com/tmobile/pacbot) ⭐ 1,310 | 🐛 138 | 🌐 Java | 📅 2022-12-08: Policy as Code Bot.
* [Forseti security](https://github.com/forseti-security/forseti-security) ⚠️ Archived: GCP inventory monitoring and policy enforcement tool.
* [aws\_pwn](https://github.com/dagrz/aws_pwn) ⭐ 1,221 | 🐛 3 | 🌐 Python | 📅 2023-08-30: A collection of AWS penetration testing junk
* [cs suite](https://github.com/SecurityFTW/cs-suite) ⭐ 1,171 | 🐛 41 | 🌐 Shell | 📅 2022-12-08: Tool for auditing the security posture of AWS/GCP/Azure.
* [cloudlist](https://github.com/projectdiscovery/cloudlist) ⭐ 1,042 | 🐛 5 | 🌐 Go | 📅 2026-08-11: Listing Assets from multiple Cloud Providers.
* [ElectricEye](https://github.com/jonrau1/ElectricEye) ⭐ 1,042 | 🐛 14 | 🌐 Python | 📅 2026-02-09: Continuously monitor AWS services for configurations.
* [awspx](https://github.com/FSecureLABS/awspx) ⭐ 1,018 | 🐛 12 | 🌐 Python | 📅 2022-10-04: A graph-based tool for visualizing effective access and resource relationships within AWS.
* [Zeus](https://github.com/DenizParlak/Zeus) ⭐ 718 | 🐛 4 | 🌐 Shell | 📅 2020-02-04: AWS Auditing & Hardening Tool.
* [diffy](https://github.com/Netflix-Skunkworks/diffy) ⭐ 629 | 🐛 3 | 🌐 Python | 📅 2024-01-11: Diffy is a digital forensics and incident response (DFIR) tool developed by Netflix.
* [azucar](https://github.com/nccgroup/azucar) ⚠️ Archived: A security auditing tool for Azure environments
* [cloud-forensics-utils](https://github.com/google/cloud-forensics-utils) ⭐ 507 | 🐛 25 | 🌐 Python | 📅 2026-08-12: A python lib for DF & IR on the cloud.
* [Hammer](https://github.com/dowjones/hammer) ⭐ 450 | 🐛 33 | 🌐 Python | 📅 2023-07-17: A multi-account cloud security tool for AWS. It identifies misconfigurations and insecure data exposures within most popular AWS resources.
* [dftimewolf](https://github.com/log2timeline/dftimewolf) ⭐ 352 | 🐛 4 | 🌐 Python | 📅 2026-08-10: A multi-cloud framework for orchestrating forensic collection, processing and data export.
* [Smogcloud](https://github.com/BishopFox/smogcloud) ⭐ 351 | 🐛 2 | 🌐 Go | 📅 2020-07-20: Find cloud assets that no one wants exposed.
* [aws\_ir](https://github.com/ThreatResponse/aws_ir) ⭐ 344 | 🐛 14 | 🌐 Python | 📅 2021-07-23: Python installable command line utility for mitigation of instance and key compromises.
* [Cloud-Katana](https://github.com/Azure/Cloud-Katana) ⚠️ Archived: Automate the execution of simulation steps in multi-cloud and hybrid cloud environments.
* [aws-firewall-factory](https://github.com/globaldatanet/aws-firewall-factory) ⭐ 257 | 🐛 16 | 🌐 TypeScript | 📅 2025-11-17: Deploy, update, and stage your WAFs while managing them centrally via FMS.
* [Cloudmarker](https://github.com/cloudmarker/cloudmarker) ⚠️ Archived: A cloud monitoring tool and framework.
* [Cloud Sniper](https://github.com/cloud-sniper/cloud-sniper) ⭐ 189 | 🐛 0 | 🌐 Python | 📅 2024-04-17: A platform designed to manage Cloud Security Operations.
* [Metabadger](https://github.com/salesforce/metabadger) ⚠️ Archived: Prevent SSRF attacks on AWS EC2 via automated upgrades to the more secure Instance Metadata Service v2 (IMDSv2).
* [SkyWrapper](https://github.com/cyberark/SkyWrapper) ⭐ 107 | 🐛 1 | 🌐 Python | 📅 2021-03-25: Tool helps to discover suspicious creation forms and uses of temporary tokens in AWS.
* [InfraScan](https://infrascan.soldevelo.com/): An Advanced Infrastructure Auditor by SolDevelo for AWS cost antipatterns, IaC security issues, and container vulnerabilities.
* [Open policy agent](https://www.openpolicyagent.org/): Policy-based control tool.

## Container

* [Falco](https://github.com/falcosecurity/falco) ⭐ 9,264 | 🐛 69 | 🌐 C++ | 📅 2026-08-03: Container runtime security.
* [mkit](https://github.com/darkbitio/mkit) ⚠️ Archived: Managed kubernetes inspection tool.
* [auditkube](https://github.com/opszero/auditkube) ⭐ 117 | 🐛 2 | 🌐 HCL | 📅 2026-08-13: Audit for for EKS, AKS and GKE for HIPAA/PCI/SOC2 compliance and cloud security.
* [Open policy agent](https://www.openpolicyagent.org/): Policy-based control tool.

## SaaS

* [cloudsplaining](https://github.com/salesforce/cloudsplaining) ⭐ 2,243 | 🐛 28 | 🌐 JavaScript | 📅 2026-08-11: An AWS IAM Security Assessment tool that identifies violations of least privilege and generates a risk-prioritized report.
* [Policy Sentry](https://github.com/salesforce/policy_sentry) ⭐ 2,166 | 🐛 9 | 🌐 Python | 📅 2026-08-09: IAM Least Privilege Policy Generator.
* [binaryalert](https://github.com/airbnb/binaryalert) ⭐ 1,454 | 🐛 43 | 🌐 Python | 📅 2023-12-12: Serverless S3 yara scanner.
* [SkyArk](https://github.com/cyberark/SkyArk) ⭐ 911 | 🐛 6 | 🌐 PowerShell | 📅 2024-12-17: Tool to helps to discover, assess and secure the most privileged entities in Azure and AWS.
* [GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute) ⭐ 572 | 🐛 7 | 🌐 Python | 📅 2023-05-26: A script to enumerate Google Storage buckets.
* [Lambda Guard](https://github.com/Skyscanner/LambdaGuard) ⚠️ Archived: AWS Lambda auditing tool.
* [Serverless Goat](https://github.com/OWASP/Serverless-Goat) ⭐ 330 | 🐛 11 | 🌐 Python | 📅 2024-07-30: A serverless application demonstrating common serverless security flaws.
* [IAM Zero](https://github.com/common-fate/iamzero) ⭐ 259 | 🐛 20 | 🌐 Go | 📅 2023-03-06: Detects identity and access management issues and automatically suggests least-privilege policies.
* [FestIN](https://github.com/cr0hn/festin) ⭐ 233 | 🐛 0 | 🌐 Python | 📅 2020-12-04: S3 bucket finder and content discover.
* [aws-allowlister](https://github.com/salesforce/aws-allowlister) ⚠️ Archived: Automatically compile an AWS Service Control Policy with your preferred compliance frameworks.
* [Cloud Guardrails](https://github.com/salesforce/cloud-guardrails) ⚠️ Archived: Rapidly cherry-pick cloud security guardrails by generating Terraform files that create Azure Policy Initiatives.
* [Function Shield](https://github.com/puresec/FunctionShield) ⭐ 40 | 🐛 0 | 📅 2019-10-29: Protection/destection lib of aws lambda and gcp function.
* [S3 Inspector](https://github.com/kromtech/s3-inspector): Tool to check AWS S3 bucket permissions.

## Penetration testing/learning

* [cloudgoat](https://github.com/RhinoSecurityLabs/cloudgoat) ⭐ 3,692 | 🐛 23 | 🌐 Python | 📅 2026-04-28: "Vulnerable by Design" AWS deployment tool.
* [AWSGoat](https://github.com/ine-labs/AWSGoat) ⭐ 2,041 | 🐛 12 | 🌐 PHP | 📅 2025-05-20: AWSGoat is a vulnerable by design AWS infrastructure featuring OWASP Top 10 web application security risks (2021) and AWS service based misconfigurations.
* [TerraGoat](https://github.com/bridgecrewio/terragoat) ⭐ 1,304 | 🐛 60 | 🌐 HCL | 📅 2025-07-13: Bridgecrew's "Vulnerable by Design" Terraform repository.
* [CloudBrute](https://github.com/0xsha/CloudBrute) ⭐ 1,144 | 🐛 0 | 🌐 Go | 📅 2025-03-09: A multiple cloud enumerator.
* [Sadcloud](https://github.com/nccgroup/sadcloud) ⭐ 785 | 🐛 9 | 🌐 HCL | 📅 2023-10-14: Tool for spinning up insecure AWS infrastructure with Terraform.
* [ccat](https://github.com/RhinoSecurityLabs/ccat) ⭐ 652 | 🐛 2 | 🌐 Python | 📅 2019-11-21: Cloud Container Attack Tool.
* [Leonidas](https://github.com/FSecureLABS/leonidas) ⭐ 616 | 🐛 9 | 🌐 Python | 📅 2024-11-28: A framework for executing attacker actions in the cloud.
* [WrongSecrets](https://github.com/commjoen/wrongsecrets) ⭐ 0 | 🐛 0 | 📅 2026-04-18: A vulnerable app which demonstrates how to not use secrets. With AWS/Azure/GCP support.
* [Pwned Labs](https://pwnedlabs.io): Free hosted labs for learning cloud security.

## Native tools

* AWS
  * [Artifact](https://aws.amazon.com/artifact/): Compliance report selfservice.
  * [Audit manager](https://aws.amazon.com/audit-manager/): Continuously audit for AWS usage.
  * [Certificate Manager](https://aws.amazon.com/certificate-manager/): Private CA and certificate management service.
  * [CloudTrail](https://aws.amazon.com/cloudtrail/): Record and log API call on AWS.
  * [Config](https://aws.amazon.com/config/): Configuration and resources relationship monitoring.
  * [Elastic Disaster Recovery](https://aws.amazon.com/disaster-recovery/): Application recovery service.
  * [Detective](https://aws.amazon.com/detective/): Analyze and visualize security data and help security investigations.
  * [Firewall Manager](https://aws.amazon.com/firewall-manager/): Firewall management service.
  * [GuardDuty](https://aws.amazon.com/guardduty/): IDS service
  * [CloudHSM](https://aws.amazon.com/cloudhsm/): HSM service.
  * [Inspector](https://aws.amazon.com/inspector/): Vulnerability discover and assessment service.
  * [KMS](https://aws.amazon.com/kms/): KMS service
  * [Macie](https://aws.amazon.com/macie/): Fully managed data security and data privacy service for S3.
  * [Network Firewall](https://aws.amazon.com/network-firewall/): Network firewall service.
  * [Secret Manager](https://aws.amazon.com/secrets-manager/): Credential management service.
  * [Security Hub](https://aws.amazon.com/security-hub/): Integration service for other AWS and third-party security service.
  * [Shield](https://aws.amazon.com/shield/): DDoS protection service.
  * [Single Sign-On](https://aws.amazon.com/single-sign-on/): Service of centrally manage access AWS or application.
  * [ThreatMapper](https://github.com/deepfence/ThreatMapper) ⭐ 5,310 | 🐛 144 | 🌐 TypeScript | 📅 2026-06-01: Identify vulnerabilities in running containers, images, hosts and repositories.
  * [VPC Flowlog](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html): Log of network traffic.
  * [WAF](https://aws.amazon.com/waf/): Web application firewall service.
* Azure
  * [Application Gateway](https://azure.microsoft.com/en-us/services/application-gateway/): L7 load balancer with optional WAF function.
  * [DDoS Protection](https://azure.microsoft.com/en-us/services/ddos-protection/): DDoS protection service.
  * [Dedicated HSM](https://azure.microsoft.com/en-us/services/azure-dedicated-hsm/): HSM service.
  * [Key Vault](https://azure.microsoft.com/en-us/services/key-vault/): KMS service
  * [Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/): API log and monitoring related service.
  * [Security Center](https://azure.microsoft.com/en-us/services/security-center/): Integration service for other Azure and third-party security service.
  * [Sentinel](https://azure.microsoft.com/zh-tw/services/azure-sentinel/): SIEM service.
* GCP
  * [Access Transparency](https://cloud.google.com/access-transparency): Transparency log and control of GCP.
  * [Apigee Sense](https://cloud.google.com/apigee/api-management/apigee-sense): API security monitoring, detection, mitigation.
  * [Armor](https://cloud.google.com/armor): DDoS protection and WAF service
  * [Asset Inventory](https://cloud.google.com/asset-inventory): Asset monitoring service.
  * [Assured workloads](https://cloud.google.com/assured-workloads/): Secure and compliant workloads.
  * [Audit Logs](https://cloud.google.com/audit-logs): API logs.
  * [Binanry Authorization](https://cloud.google.com/binary-authorization/): Binary authorization service for containers and serverless.
  * [Cloud HSM](https://cloud.google.com/hsm): HSM service.
  * [Cloud IDS](https://cloud.google.com/intrusion-detection-system/): IDS service.
  * [Confidential VM](https://cloud.google.com/compute/confidential-vm/): Encrypt data in use with VM.
  * [Context-aware Access](https://cloud.google.com/context-aware-access): Enable zero trust access to applications and infrastructure.
  * [DLP](https://cloud.google.com/dlp): DLP service:
  * [EKM](https://cloud.google.com/ekm): External key management service
  * [Identity-Aware Proxy](https://cloud.google.com/iap): Identity-Aware Proxy for protect the internal service.
  * [KMS](https://cloud.google.com/kms): KMS service
  * [Policy Intelligence](https://cloud.google.com/policy-intelligence): Detect the policy related risk.
  * [Security Command Center](https://cloud.google.com/security-command-center): Integration service for other GCP security service.
  * [Security Scanner](https://cloud.google.com/security-scanner): Application security scanner for GAE, GCE, GKE.
  * [Shielded VM](https://cloud.google.com/compute/shielded-vm/): VM with secure boot and vTPM.
  * [Event Threat Detection](https://cloud.google.com/event-threat-detection): Threat dection service.
  * [VPC Service Controls](https://cloud.google.com/vpc-service-controls): GCP service security perimeter control.

# Reading Materials

* [AWS](#aws)
* [Azure](#azure)
* [GCP](#gcp)
* [Others](#others)

## AWS

1. [AWS-IAM-Privilege-Escalation by RhinoSecurityLabs](https://github.com/RhinoSecurityLabs/AWS-IAM-Privilege-Escalation) ⭐ 930 | 🐛 1 | 📅 2019-07-25: A centralized source of all AWS IAM privilege escalation methods.
2. [ThreatModel for Amazon S3](https://github.com/trustoncloud/threatmodel-for-aws-s3) ⭐ 167 | 🐛 2 | 🌐 Open Policy Agent | 📅 2026-08-03: Library of all the attack scenarios on Amazon S3, and how to mitigate them following a risk-based approach
3. [Overiew of AWS Security](https://aws.amazon.com/security/)
4. [MITRE ATT\&CK Matrices of AWS](https://attack.mitre.org/matrices/enterprise/cloud/aws/)
5. [AWS security workshops](https://github.com/aws-samples/aws-security-workshops)

## Azure

1. [MicroBurst by NetSPI](https://github.com/NetSPI/MicroBurst) ⭐ 2,415 | 🐛 5 | 🌐 PowerShell | 📅 2026-06-29: A collection of scripts for assessing Microsoft Azure security
2. [Azure security center workflow automation](https://github.com/Azure/Azure-Security-Center/tree/master/Workflow%20automation) ⭐ 1,928 | 🐛 50 | 🌐 PowerShell | 📅 2026-07-09
3. [Overiew of Azure Security](https://azure.microsoft.com/en-us/overview/security/)
4. [Azure security fundamentals](https://docs.microsoft.com/en-us/azure/security/fundamentals/)
5. [MITRE ATT\&CK Matrices of Azure](https://attack.mitre.org/matrices/enterprise/cloud/azure/)

## GCP

1. [Security response automation](https://github.com/GoogleCloudPlatform/security-response-automation) ⚠️ Archived
2. [GKE security scenarios demo](https://github.com/GoogleCloudPlatform/gke-security-scenarios-demo) ⚠️ Archived
3. [Overiew of GCP Security](https://cloud.google.com/security)
4. [MITRE ATT\&CK Matrices of GCP](https://attack.mitre.org/matrices/enterprise/cloud/gcp/)

## Others

1. [Appsecco provides training](https://github.com/appsecco/breaking-and-pwning-apps-and-servers-aws-azure-training) ⭐ 951 | 🐛 1 | 🌐 CSS | 📅 2022-11-26
2. [Cloud Security Research by RhinoSecurityLabs](https://github.com/RhinoSecurityLabs/Cloud-Security-Research) ⭐ 392 | 🐛 0 | 🌐 Python | 📅 2020-04-23
3. [CSA cloud security guidance v4](https://cloudsecurityalliance.org/artifacts/security-guidance-v4/)
4. [Cloud Risk Encyclopedia by Orca Security](https://orca.security/resources/cloud-risk-encyclopedia/): 900+ documented cloud security risks, with ability to filter by cloud vendor, compliance framework, risk category, and criticality.

# Free Courses

1. [AWS Security](https://www.youtube.com/playlist?list=PL0-xwzAwzllw_dvNfabV28-bpAEoMchd3)

# Paid Courses

1. [DevSecOps – Kubernetes DevOps & Security](https://kodekloud.com/courses/devsecops)
2. [DevSecOps: Insecure Docker Registry](https://www.pentesteracademy.com/course?id=48)
3. [Learn Cloud Security, Kubernetes, DevSecOps, and more](https://www.appsecengineer.com)
4. [Certified Kubernetes Security Specialist (CKS)](https://kodekloud.com/courses/certified-kubernetes-security-specialist-cks)

# Bootcamps

1. [On-Demand: DevSecOps: Beginner Edition Bootcamp](https://bootcamps.pentesteracademy.com/course/devsecops-on-demand)
2. [On-Demand: Cloud Security: AWS Edition Bootcamp](https://bootcamps.pentesteracademy.com/course/cloud-security-aws-on-demand)
3. [On-Demand: Container Security: Beginner Edition Bootcamp](https://bootcamps.pentesteracademy.com/course/container-security-on-demand)

# Trainings

1. [Attacking and Defending AWS](https://resources.tryhackme.com/attacking-and-defending-aws)

# Certifications

1. [CCSP – Certified Cloud Security Professional](https://www.isc2.org/Certifications/CCSP)
2. [AWS Certified Security - Specialty](https://aws.amazon.com/certification/certified-security-specialty)
3. [Microsoft Certified: Azure Security Engineer Associate](https://learn.microsoft.com/en-us/certifications/azure-security-engineer)
4. [Certified Kubernetes Security Specialist (CKS)](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist)

# Resource

* [AWS](#aws-1)
* [Others](#others-1)

## AWS

1. [Bucket search by grayhatwarfare](https://buckets.grayhatwarfare.com/)

## Others

1. [Mapping of On-Premises Security Controls vs. Major Cloud Providers Services](https://www.eventid.net/docs/onprem_to_cloud.asp)

# Contributing

See [contributing](https://github.com/4ndersonLin/awesome-cloud-security/blob/master/CONTRIBUTING.md) ⭐ 2,475 | 🐛 19 | 📅 2026-03-17

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
