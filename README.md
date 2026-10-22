# AWS VPC Networking Lab

## Project Overview

This project documents my hands-on practice configuring networking components in Amazon Web Services (AWS). It focuses on Amazon Virtual Private Cloud (VPC), subnet configuration, routing, internet connectivity, and network access.

## Objectives

- Create and inspect an AWS VPC.
- Configure two subnets within the VPC.
- Attach an Internet Gateway.
- Configure a route table with a default route to the Internet Gateway.
- Associate subnets with a route table.
- Explore EC2 connectivity and SSH access.

## AWS Services and Concepts

- Amazon VPC
- Subnets
- Internet Gateway
- Route tables and subnet associations
- Security groups
- Amazon EC2 and SSH connectivity

## Architecture and Configuration

The lab included a VPC named `MyGroupVPC`, two subnets, an Internet Gateway named `MyInternetGateway`, and a route table named `PublicRouteTable`.

The documented default route was `0.0.0.0/0` pointing to the Internet Gateway. This route provides a path toward the internet; actual internet connectivity also depends on subnet routing, public IP addressing, security rules, and other configuration requirements.

## Evidence

Screenshots documenting the lab are available in the [`screenshots/`](screenshots/) directory.

The evidence covers VPC creation, subnet configuration, Internet Gateway attachment, route table configuration, subnet associations, and EC2 SSH connectivity.

## Key Learning Outcomes

- Understanding how VPCs and subnets organize AWS network resources.
- Learning how route tables direct traffic.
- Understanding the role of an Internet Gateway in internet routing.
- Recognizing how network routes and security controls work together.
- Practising technical documentation and evidence-based troubleshooting.

## Security and Cost Management

AWS resources used for the exercise have been cleaned up after the lab.

Screenshots should be reviewed to ensure they do not expose credentials, private keys, or sensitive account information.

## Project Status

Completed learning exercise. This repository documents the configuration and concepts practised during the lab.
