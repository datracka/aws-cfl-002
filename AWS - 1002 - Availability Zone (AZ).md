a physical location isolated into a [[AWS - 1004 - Region]]. It is one or more Data Centers. 

DataCenters in a Region are isolated from each others, but close enough to provide low-latency. 

High availability: Run in 3 AZ in case one or two fail.

AZs are represented by Region code, followed by a letter eg: us-east-1a

The AZ is related to the Region through the Subnet. when you choose a subnet you are selecting the Data Center. 

AZ in a [[AWS - 1004 - Region]] are fully redundant between them. 

They are within 100 KM (60 miles).


![[availability-zone.png]]

