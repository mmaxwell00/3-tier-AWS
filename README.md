# 3-tier-AWS

Three-tier Kubernetes application architecture on AWS with high availability and redundancy.

## Overview

This repository contains architectural documentation for a robust, scalable three-tier application designed to run on Amazon EKS (Elastic Kubernetes Service).

## Architecture Highlights

- **High Availability**: Multi-AZ deployment with 2 instances per tier
- **Scalability**: Horizontal Pod Autoscaling and cluster autoscaling
- **Security**: Private subnets and proper network segmentation
- **Consistent Storage**: Amazon RDS Multi-AZ or persistent volumes

## Documentation

- [Three-Tier Kubernetes Architecture](./three-tier-k8s-aws-architecture.md) - Complete architectural overview and implementation guide

## Tiers

1. **Frontend (Presentation Layer)**: React/Angular/Vue.js applications
2. **Backend (Application Layer)**: Node.js/Java/Python API services
3. **Database (Data Layer)**: Amazon RDS or StatefulSet with persistent storage

## Key Features

- ✅ Multi-AZ deployment across 2+ availability zones
- ✅ 2 replicas per tier for redundancy
- ✅ Auto-healing and failover capabilities
- ✅ Load balancing at each tier
- ✅ Secure network architecture with private subnets

## Getting Started

Refer to the [architecture documentation](./three-tier-k8s-aws-architecture.md) for detailed implementation steps and best practices.

---

*Created: December 12, 2025*