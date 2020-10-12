# 2020-openvpn-cloudformation

This CloudFormation template sets up a new virtual private cloud (VPC),
adds a new EC2 instance to the VPC, and sets up an OpenVPN server and a
dnsmasq DNS server on the private instance.

It also provides SSM documents to create/delete clients, and an S3 bucket
that it uses to provide clients with their credentials.

