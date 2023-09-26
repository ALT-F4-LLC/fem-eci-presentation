---
marp: true
theme: default
class:
  - invert
  - lead
---

# Enterprise Cloud Infrastructure

Defining and standardizing Enterprise Cloud Infrastructure for organizations.

---

# Introduction to Teacher

![hello](https://media.giphy.com/media/3ornk57KwDXf81rjWM/giphy.gif)

---

# Introduction to Teacher

## Erik Reinert aka "Blackglasses"

- Senior Software Engineer
- Content Creator (@TheAltF4Stream on Twitch and YouTube)
- Flowchart Artist
- Problem Solver

---

# Introduction to Teacher

## Expierence Paths

- Started with frontend (2+ years)
- Followed curiosity to backend (2+ years)
- Continued curiosity to fullstack (2+ years)
- Found passion in DevOps (currently - 4+ years)

---

# Introduction to Course

![welcome](https://media.giphy.com/media/XD9o33QG9BoMis7iM4/giphy.gif)

---

# Introduction to Course

A quote from generative AI:

> If you don't know what problems you are solving, you can't solve them.

---

# Introduction to Course

Building of what we learned in "DevOps for Developers" our goals in this course are:

- Break down common problems an organization has
- Identify who solving these problems helps the most
- Explain why it is important to solve these problems
- Build a solution to these problems using standardized practices

---

# Introduction to Course

## Is "DevOps for Developers" course required for this course?

- No, but it will help.

---

# Introduction to Course

## Should I watch "DevOps for Developers" course anyways?

![yup](https://media.giphy.com/media/6cFcUiCG5eONW/giphy.gif)

---

# Introduction to Course

We will follow the three W's of strategy for our organization challenges:

- What problem are we trying to solve?
- Who are we solving it for?
- Why are we solving this problem?

###### Explained further in "DevOps for Developers" course.

---

# Introduction to Course

## So... what are our problems?

![](https://media.giphy.com/media/fd1TSJqq3b4GI/giphy.gif)

---

# Introduction to Course

## Ask our first W: What problem(s) are we trying to solve?

---

# Introduction to Course

## What problem(s) are we trying to solve as an organization?

- Access Control and Permissions
- Software lifecycles
- Supporting infrastructure
- Developer expierence (aka DX)

###### This is only a short list of problems, but we will focus on these for this course.

---

# Introduction to Course

## Ask our second W: Who are we solving problems for?

---

# Introduction to Course

## Who are we solving problems for?

- Developers
- Quality Assurance
- IT
- Others

---

# Introduction to Course

## Ask our third W: Why are we solving this problem?

---

# Introduction to Course

## Why are we solving this problem?

- Organization needs (internal)
- Organization units needs (product, service, etc)

---

# Organization Problems

![](https://media.giphy.com/media/FjhCTrjPaPy6s/giphy.gif)

---

# Organization Problems

### What are common problems organizations face?

---

# Organization Problems

- Role-Based Access Control
- Domains & DNS
- Networking
- Resources (compute, storage, etc)

---

# Organization Problems

## Role-Based Access Control

- Organizational Units (teams)
- Individuals (developers)
- Outside Contributors (third-parties)

---

# Organization Problems

## Domains & DNS

- Private vs public TLDs (top-level domains)
- DNS management and routing

---

# Organization Problems

## Networking

- Private networks
- Public networks
- Firewall security boundaries
- Secure connections (VPN, etc)

---

# Organization Problems

## Resources (compute, storage, etc)

- Amazon Web Services
- Google Cloud Platform
- Azure Cloud
- Others (boutique or self-hosting)

---

# Developer Problems

![help](https://media.giphy.com/media/h5Kj3oDLtuh6NoRy5x/giphy.gif)

---

# Developer Problems

- Source Control
- Service Management
- Continuous Integration
- Continuous Delivery

###### Developers ONLY deal with code and mechanisms to deploying it.

---

# Developer Problems

## Source Control

- Repository management
- Branch protections & policies
- Code reviews & approvals

###### Developers MUST have standardized procedures to manage code efficiently.

---

# Developer Problems

## Service Management

- Configuration
- Provisioning

###### Developers EMPOWERED to manage their own services.

---

# Developer Problems

## Continuous Integration

- Building artifacts
- Testing changes
- Code coverage
- Code quality

###### Developers MUST have dependable and reliable pipelines.

---

# Developer Problems

## Continuous Delivery

- Deploying artifacts
- Environment releases

###### Developers EMPOWERED to deploy their own services.

---

# Developer Problems

## Did you say "developers" maintain their own deployments?

![](https://media.giphy.com/media/l0HlEMf3CdWiETeGk/giphy.gif)

---

# Developer Problems

## Why is developer empowerment important?

- Faster development cycles
- Faster feedback loops
- Faster time to market
- Faster time to value

###### DevOps teams MUST empower developers to be successful.

---

# Introduction to GitOps

![what](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMHh5OXN4ZTFyYjBrNDk2cTZwOGRsZnk2dzB5aXVsNHpwbjByczQ0aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/jdW8IvE7tlLoPfbSKY/giphy.gif)

---

# Introduction to GitOps

Another quote from generative AI:

> If you don't know what you did, you can't do it again.

---

# Introduction to GitOps

## What is GitOps? (defined by AI)

> GitOps is a paradigm or a set of practices that emphasizes using Git as a single source of truth for declarative infrastructure and applications.

###### Pretty much... GitOps is a way to manage infrastructure and applications using Git.

---

# Introduction to GitOps

## What can GitOps provide?

- Infrastructure as Code
- Automated Deployments
- Reproducibility and Rollbacks
- Enhanced Collaboration

---

# Introduction to GitOps

## Infrastructure as Code (aka IaC)

Infrastructure and application configurations are stored in a Git repository and versioned for complete history. This allows for changes to be tracked and reviewed.

###### Tracking and reviewing is crucial to scaling any enterprise organization.

---

# Introduction to GitOps

## Automated Deployments

Changes to the repo trigger automatic deployments using pipelines or other methods, ensuring the live environment matches the repo's state. This allows for changes to be deployed quickly and reliably.

###### Deploying quickly and reliably is crucial to scaling any enterprise organization.

---

# Introduction to GitOps

## Reproducibility and Rollbacks

Since all changes are tracked in Git, it's easy to roll back or recreate specific states of the infrastructure or applications. This allows for changes to be reverted or recreated quickly.

###### Reverting or recreating quickly is crucial to scaling any enterprise organization.

---

# Introduction to GitOps

## Enhanced Collaboration

Developers use familiar Git-based workflows for both application and infrastructure changes. This allows for changes to be made by anyone in the organization with proper permissions.

###### Empowering individuals to contribute is crucial to scaling any enterprise organization.

---

# Introduction to GitOps

## TLDR for GitOps (said by AI)

> Essentially, with GitOps, if you want to know the current state of your system or how it looks, you just look at your Git repo.

---

# Introduction to GitOps

## TLDR of TLDR for GitOps (said by AI)

> If you want to change the system, you change the repo.

---

# Automation Tools

![hmm](https://media.giphy.com/media/xT5LMyV3wwx20bNKtq/giphy.gif)

---

# Automation Tools

## Industry Standards

- Terraform\* (widely used)
- Pulumi (growing community)

---

# Automation Tools

## What about this "OpenTofu" thing?

![ehh](https://media.giphy.com/media/l4Ep6uxU6aedrYUik/giphy.gif)

###### OpenTofu is a new open-source automation tool that is gaining popularity.

---

# Automation Tools

## Not-so-Industry Standards

- \*OpenTofu (maybe)

###### OpenTofu, currently, only helps licensing with developers or providers who want to resell Terraform-like solutions. This could change in the future or it could also be another tool.

---

# Automation Tools

## Terraform

- declarative based configuration
- very low entrypoint for starting
- massive developer support

---

# Automation Tools

## Terraform

```hcl
resource "aws_vpc" "main" {
  cidr_block       = "10.0.0.0/16"
  instance_tenancy = "default"

  tags = {
    Name = "main"
  }
}
```

###### Example of creating an AWS VPC (Virtual Private Cloud) using Terraform.

---

# Automation Tools

## Pulumi

- imperative language configuration (NodeJS, Python, Go, .NET, Java & YAML)
- more "customized" solutions with possibly higher entrypoint
- more "flexible" solutions with ability to use any language

---

# Automation Tools

## Pulumi

```
import * as pulumi from "@pulumi/pulumi";
import * as aws from "@pulumi/aws";

const main = new aws.ec2.Vpc("main", {
    cidrBlock: "10.0.0.0/16",
    instanceTenancy: "default",
    tags: {
        Name: "main",
    },
});
```

###### Example of creating an AWS VPC (Virtual Private Cloud) using Pulumi in NodeJS.

---

# Automation Tools

## So... which one should I use?

![](https://media.giphy.com/media/k56oRtCg218Z2/giphy.gif)

---

# Automation Tools

## How to choose?

- Focus on the problems you are trying to solve
- Focus on how efficient you want to be
- Focus on the tools you are already using

###### Do not focus on what is "best" or "most popular" unless you want to waste time.

---

# Automation Tools

## Terraform Cases

- Desire to use declarative configuration
- Desire to use a single language for all configurations
- Desire to use a single tool for all configurations

---

# Automation Tools

## TLDR; Terraform Cases

![](https://media.giphy.com/media/26AHLNr8en8J3ovOo/giphy.gif)

###### Terraform is a great choice for large or small teams with fast iteration cycles.

---

# Automation Tools

## Pulumi Cases

- Desire to use imperative configuration (NodeJS, Python, Go, .NET, Java & YAML)
- Desire to use multiple languages for configurations
- Desire to use multiple tools for configurations

###### Pulumi is covered more in-depth in the "DevOps for Developers" course.

---

# Automation Tools

## TLDR; Pulumi Cases

![perfection](https://media.giphy.com/media/9WXyFIDv2PyBq/giphy.gif)

###### Pulumi is a great choice for organizations with specific needs or scaling requirements.

---

# Automation Providers

![help](https://media.giphy.com/media/sDcfxFDozb3bO/giphy.gif)

---

# Automation Providers

## Should you use an automation provider?

- Standardized practices
- Collaboration features
- Additional features (cost management, etc)

---

# Automation Providers

## Do you need to spend money on providers?

- No, but it will help focus money on other problems.

###### This decision is up to the organization.

---

# Automation Providers

## What if I don't want to spend money on providers?

- You can build your own solutions
- You can use open-source solutions
- You can pay engineers to build solutions (employees or contractors)

###### No matter what, you will spend money on automation.

---

# Automation Providers

## What are some automation providers?

- Terraform Cloud\*
- Pulumi Cloud
- Env0, Spacelift, and others

###### There are many more, but these are the most common.

---

# Automation Providers

## Terraform Cloud

- Industry standard for enterprise
- Maintains state of infrastructure
- Provides access control features
- Includes infrastructure (no hosting required)

###### Terrafom Cloud is a great choice for large or small teams collaborating on infrastructure.

---

# Automation Providers

## Pulumi Cloud

- Alternative to Terraform Cloud
- Maintains state of infrastructure
- No pipelines (requires hosting)

###### Pulumi Cloud is a great choice for organizations with existing pipelines or hosting.

---

# Automation Providers

## Env0, Spacelift, and others

- Alternatives to Terraform Cloud and Pulumi Cloud
- Includes infrastructure (no hosting required)
- Supports multiple types of automation tools (both Terraform and Pulumi, etc)
- Additional features (cost management, etc)

###### These platforms are great when you want to use multiple tools or solutions.

---

# Automation Providers

## How to choose?

![pick](https://media.giphy.com/media/WRQBXSCnEFJIuxktnw/giphy.gif)

---

# Automation Providers

## How to choose?

- Focus on the problems you are trying to solve
- Focus on the tools you are already using
- Focus on the features you need first

###### Do not focus on what is "best" or "most popular" unless you want to waste time.

---

# Continuous Integration & Delivery (CI/CD)

![](https://media.giphy.com/media/N8wR1WZobKXaE/giphy-downsized-large.gif)

---

# Continuous Integration & Delivery (CI/CD)

## What is continuous integration? (defined by AI)

> Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project.

###### Pretty much... CI is a way to validate code changes using automation.

---

# Continuous Integration & Delivery (CI/CD)

## What is continuous delivery? (defined by AI)

> Continuous delivery (CD) is an approach to software engineering based on producing software in short cycles.

###### Pretty much... CD is a way to deploy code changes using automation.

---

# Continuous Integration & Delivery (CI/CD)

## Are CI and CD the same thing?

![](https://media.giphy.com/media/JYZ397GsFrFtu/giphy.gif)

###### No, but they are often used together.

---

# Continuous Integration & Delivery (CI/CD)

## What is the TLDR; on differences?

- Continuous integration (CI) validates code changes
- Continuous delivery (CD) deploys code changes

###### CI and CD should exist as separate automation strategies.

---

# Continuous Integration & Delivery (CI/CD)

## Cloud Providers

- GitHub Actions\*
- GitLab CI/CD
- AWS CodePipeline
- Azure Pipelines
- Others (CircleCI, Bitbucket Pipelines, etc)

###### There are many more, but these are the most common.

---

# Continuous Integration & Delivery (CI/CD)

## Open Source

- Jenkins (not recommended)
- Drone (limited features)
- Others (Concourse, etc)

###### There are many more, but these are the most common.

---

# Continuous Integration & Delivery (CI/CD)

## Open Source (Kubernetes)

- Argo Workflows
- GoCD
- Tekton

###### There are many more, but these are the most common.

---

# Continuous Integration & Delivery (CI/CD)

## What about manual scripts?

- No... just no.

###### This is NOT recommended, but it is an option if you have specific requirements.

---

# Continuous Integration & Delivery (CI/CD)

## But seriously why not?

![](https://media.giphy.com/media/403aNkstqvOqameBHW/giphy.gif)

###### Manual scripts are not scalable or reliable.

---

# Self-Hosted vs Cloud Providers

![](https://media.giphy.com/media/l46CsTPetihC1rX9K/giphy.gif)

###### This is a common question, but it is not the right question.

---

# Self-Hosted vs Cloud Providers

## Should I self-host my infrastructure?

- No.

###### This decision is up to the organization but normally not recommended.

---

# Self-Hosted vs Cloud Providers

## It's SOO much cheaper!

- Also no.

###### This is a common misconception.

---

# Self-Hosted vs Cloud Providers

## It's SOO much cheaper!

- You will spend more money on engineers.
- You will spend more money on maintenance.
- You will spend more money on security.

###### TLDR; it's not cheaper unless you have well designed specific requirements.

---

# Self-Hosted vs Cloud Providers

## When should I self-host my infrastructure?

- You have specific requirements for a problem.

###### Self-hosting should be for isolated or separately managed infrastructure.

---

# Self-Hosted vs Cloud Providers

## Have you self-hosted infrastructure before?

- Yes. Colocation datacenter.
- Yes. Private clouds (OpenStack and VMware).

###### In both times it was not cheaper or easier and more time was spent on maintenance.

---

# Self-Hosted vs Cloud Providers

## Which cloud providers should I use?

- Amazon Web Services\*
- Google Cloud Platform
- Azure Cloud
- Others (IBM, etc)

###### There are many more, but these are the most common.

---

# Self-Hosted vs Cloud Providers

## What about others I've seen before?

- Digital Ocean
- Linode
- Others (Heroku, etc)

###### These are not considered enterprise cloud providers as they build on top of other providers.

---

# Self-Hosted vs Cloud Providers

## How can "boutique" providers help?

- They can help with specific requirements.
- They can help with specific problems.
- They can help with speed to market.

###### Boutique providers are great for small teams or organizations.

---

# Self-Hosted vs Cloud Providers

## Which cloud provider should I use?

- Evaluate your requirements
- Include possible future requirements
- Determine which provider fits your needs
- Determine which provider fits your budget
- Test with a constant proof of concept (same used for all providers)
- Document your findings and compare

###### This is not a simple decision and should be taken seriously with proper research.

---

# Time to build!

![](https://media.giphy.com/media/ipKce0fXlBQUo/giphy.gif)

###### No more talking, let's build some infrastructure!

---

# Time to build!

## Selected Providers

- Doppler (development secrets management)
  - https://dashboard.doppler.com/register
- GitHub + Actions (source control & pipelines)
  - https://github.com/signup
- Terraform Cloud (automation provider)
  - https://app.terraform.io/public/signup/account
- AWS (cloud provider)
  - https://portal.aws.amazon.com/billing/signup

---

# Time to build!

## Selected Tools

- Doppler CLI
  - https://docs.doppler.com/docs/cli
- GitHub CLI
  - https://cli.github.com/
- Terraform CLI
  - https://developer.hashicorp.com/terraform/downloads
- AWS CLI
  - https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

---

# Time to build!

## Infrastructure Overview

###### This is an example of enterprise infrastructure automation.

---

# Time to build!

## Service Overview

###### This is an example of a enterprise service automation.

---

# Time to build!

## Workshop Materials

- Terraform Cloud: https://github.com/ALT-F4-LLC/fem-eci-terraform-tfe
- Github: https://github.com/ALT-F4-LLC/fem-eci-terraform-github
- AWS:
  - Network: https://github.com/ALT-F4-LLC/fem-eci-terraform-aws-network
  - Cluster: https://github.com/ALT-F4-LLC/fem-eci-terraform-aws-cluster
- Service: https://github.com/ALT-F4-LLC/fem-eci-terraform-product-service

###### This is an example of a enterprise service automation.
