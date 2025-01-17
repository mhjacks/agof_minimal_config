# Ansible GitOps Framework Minimal Configuration Demo

## What is this?

This is a minimalistic pattern that demonstrates how to use AGOF, an Ansible GitOps Framework.

It contains configuration suitable to load a project, inventory, and template into Ansible Automation Platform, and runs the template as a job. The entire pattern depends only on the AAP controller, and the template job connects to, elevates privileges on, and gathers facts from the AAP node.

The intention is to provide an example to build on, to build more interesting patterns with.

## How do I get started?

1. Check this repository out
1. Check out the AGOF [repository](https://github.com/validatedpatterns/agof), which will serve as the provisioner for the pattern
1. Configure an `~/agof_vault.yml` file with your AWS credentials and configuration
1. This config will then load the demo [project](https://github.com/validatedpatterns-demos/agof_minimal_demo.git) into your AAP instance.
