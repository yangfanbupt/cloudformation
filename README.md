The templates help you build a Transit VPC and spoke VPC. vEOS Routers are deployed in different Avaiability Zones in both Transit VPC and Spoke VPC. The templates also automates the High Availability configurations of vEOS Router in Spoke VPC. vEOS Router is configured with public ip address.

You can use transitvpc.json to build one Transit VPC, and repeat spokevpc.json to build multiple Spoke VPC. Once templates are deployed, you can use Arista Cloud Vision Portal (CVP) to manage vEOS Router, and use configlet to push IPSEC/Routing configurations to vEOS Router to bring up the connection between Transit VPC and Spoke VPC.

The full deployment guide is hosted on Arista EOS Central https://eos.arista.com. You need an active Arista account to login and view the content.
