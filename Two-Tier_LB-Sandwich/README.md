This Lab has two parts.

Part 1: Two Tier deployment illustrating North/South East/West inspection within GCP

Part 2: Load Balancer Sandwich and X-Forward For logging

Please see Lab Guide:   IGNITE18-US-HOW-11-GCP-Workshop-Guide-github-ver20180606.pdf

Requirements
  - bootstrap buckets- two vm-series bootstrap buckets are required to complete these labs.  
     - bootstrap bucket for part 1 of the lab with the corresponding bootstrap.xml and init-config.txt
     - bootstrap bucket for part 2 of the lab with the corresponding bootstrap.xml and init-config.txt
  - modification to the .py and .yaml files 
     - bootstrap bucket name
     - bucket name for Web and DB servers startup scripts
     
Note: Licenses Bundle is for VM-Series VM-300 PAYGO bundle2.  This line in the scripts can be modifies to one of the following VM-Series images if desired.

 https://www.googleapis.com/compute/v1/projects/paloaltonetworksgcp-public/global/images/vmseries-byol-810
 https://www.googleapis.com/compute/v1/projects/paloaltonetworksgcp-public/global/images/vmseries-bundle2-810
 https://www.googleapis.com/compute/v1/projects/paloaltonetworksgcp-public/global/images/vmseries-bundle1-810
 
