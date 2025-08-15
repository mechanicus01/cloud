# Virtual Private Cloud (VPC)

## Table of Contents

- [What are VPCs?](#what-are-vpcs)
- [How to segment VPC networks](#how-to-segment-vpc-networks)
- [Using Firewall rules to restrict access to instances](#using-firewall-rules-to-restrict-access-to-instances)
- [Creating static routes to forward traffic to specific destinations](#creating-static-routes-to-forward-traffic-to-specific-destinations)
- [Global VPC Networks](#global-vpc-networks)

## What are VPCs?

A Virtual Private Cloud (VPC) is a private cloud hosted within a public cloud. It provides a secure and isolated environment for running applications and storing data. VPCs allow organizations to have more control over their cloud resources, including the ability to define their own network topology, IP address ranges, and security settings.

## How to segment VPC networks
- VPC Peering - With VPC Peering, a relationship between two VPCs can be established to exchange traffic
- Shared VPC

## Using Firewall rules to restrict access to instances

Tag webservers as "web" then write a firewall rule saying that traffic on ports 80 or 443 is allowed into all VMs with the “WEB” tag, no matter what their IP address happens to be.

## Creating static routes to forward traffic to specific destinations

## Global VPC Networks

Google VPC networks are global and can have subnets in any Google Cloud region worldwide.

## Cloud Load Balancing

## Cloud DNS & Cloud CDN

## Connecting networks to Google VPC
