# TFE_airgap_asg
TFE installation airgap mode with Auto Scaling Group









# done
- [x] create VPC
- [x] create 4 subnets, 2 for public network, 2 for private network
- [x] create internet gw and connect to public network with a route table
- [x] create nat gateway, and connect to private network with a route table
- [x] route table association with the subnets 
- [x] security group for allowing port 443 8800
- [x] transfer files to bucket
      - airgap software
      - license
      - Download the installer bootstrapper
- [x] Get an Airgap software download
- [x] RDS PostgreSQL database

# to do
- [ ] install TFE
- [ ] Auto scaling launch configuration
- [ ] Generate certificates with Let's Encrypt to use
- [ ] import TLS certificate
- [ ] create a LB (check Application Load Balancer or Network Load Balancer)
- [ ] publish a service over LB TFE dashboard and TFE application
- [ ] Auto scaling group creating
- [ ] create DNS CNAME for website to loadbalancer DNS
