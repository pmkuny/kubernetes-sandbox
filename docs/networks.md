| System | Name | Type | Purpose | AZ | CIDR |
|--------|------|------|---------|----|------|
|Ceph | Ceph Network| VPC | | | 10.10.0.0/16 |
|Ceph | control-uw2a | Subnet | Control Plane | us-west-2a | 10.10.10.0/24 |
|Ceph | control-uw2b | Subnet | Control Plane | us-west-2b | 10.10.20.0/24 |
|Ceph | public-uw2a | Subnet | Public Nodes | us-west-2a | 10.10.1.0/24 |
|Ceph | public-uw2b | Subnet | Public Nodes | us-west-2b | 10.10.2.0/24 |
|Ceph | storage-uw2a | Subnet | Storage Plane | us-west-2a | 10.10.30.0/24 |
|Ceph | storage-uw2b | Subnet | Storage Plane | us-west-2b| 10.10.40.0/24 |
|Kubernetes| Kubernetes | VPC | | | 10.20.0.0/16 |
|Kubernetes | control-uw2a | Subnet | Control Plane | us-west-2a | 10.20.10.0/24 |
|Kubernetes | control-uw2b | Subnet | Control Plane | us-west-2b | 10.20.20.0/24 |
|Kubernetes | worker-uw2a | Subnet | Worker PLane | us-west-2a | 10.20.30.0/24 |
|Kubernetes | worker-uw2b | Subnet | Worker PLane | us-west-2b | 10.20.40.0/24 |
|Kubernetes | public-uw2a | Subnet | Public | us-west-2a | 10.20.1.0/24 |
|Kubernetes | public-uw2b | Subnet | Public | us-west-2b | 10.20.2.0/24 |
|Sandbox | Sandbox | VPC | | | 10.30.0.0/16 |
|Sandbox | admin-uw2a | Subnet | Management | us-west-2a | 10.30.5.0/28 |



