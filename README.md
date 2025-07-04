# AWS Day 5 – EC2 NGINX Setup

## Steps Performed

1. Launched EC2 instance (Amazon Linux)
2. Opened ports 22 (SSH) and 80 (HTTP) in security group
3. Connected to EC2 via SSH:
# AWS Day 6 – EBS Volume Format & Mounting

Steps covered:
- Attach EBS volume
- Format to ext4
- Mount to /mnt/mydata
- Setup auto-mount using /etc/fstab
### ✅ Day 9: CloudWatch Custom Metrics from EC2

- Launched new EC2 in us-east-1d for CloudWatch testing.
- Installed and configured CloudWatch agent using wizard.
- Selected metrics: CPU, Memory, Disk, Swap, DiskIO.
- Verified metrics under CWAgent namespace in CloudWatch.
- Understood EC2 instance IAM role requirement for full metadata integration.
