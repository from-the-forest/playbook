# Playbook

## APIs

- GraphQL first (federation).  You can abstract into other services as needed.

## Infrastructure

Principles:
- be cloud agnostic by using terraform to reduce cost, and maintain flexability.
- deployments via CI (circleci)
- don't prematurely scale - but scale automatically via k8s
