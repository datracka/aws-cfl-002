when you want to upload data / files without worrying the underlying infrastructure.

- EBS: Block
	- Attached to a EC2
	- FC / iSCSI
	- suitable for VM attached 1 to 1
	- SSD, IOPS, SSD, Cold HHD
- EFS: File
	- NFS / SMB
	- Suitable for VM shared between multiple users / VM
- S3
	- Object (Data / Metadata and Unique ID)
	- **Not unlimited storage** / unlimited buckets
	- Unlimited number of objects in a bucket
	- 5Tbytes max object Size
	- No locks (multiple reads/ writes)
	- Lifecycle policies
- Storage Gateway
	- Extends your on-premise storage to the cloud
		- File Gateway. Extension to S3
		- Volume Gateway. Backup to S3
		- Tape Ga; teway. Tape Backup, -> cost effective
- AWS Snow family: Physical devices to transfer data IN / OUT

## S3

Manage data as Objects

S3 Object
 - key
 - value
 - version ID
 - metadata

S3 Bucket
	- Unique name (universal namespace). 
	- Max file of 5T in a bucket.
	- Unlimited amount of files.
	- you pay what you store for.
	- You don't mind the file system of the HD itself.

##  Storage Classes

Trades Price for Time / Accessibility and Durability.

- S3 Standard
	- 99% Availability. Replicate through AZ 
- S3 Standard -IA
	- Cheaper if you access less than once a month. Fee is another retrieval is applied
	- 50% discount 
- S3 one Zone-IA
	- Just one AZ. Availability 99.5% 20% cheaper than S3 Standard -IA, less durability, data could get destroyed and retrieval fee is applied.
- S3 Glacier
	- Very cheap
	- Retrieval data can take minutes od hour
- S3 Glacier Deep Archive
	- lowest cost, 12 hours retrieval
- S3 Intelligent tiering -> ML to select the most appropriate storage class

## AWS Snow Family 

to move data in and out the cloud

It lives in S3 object storage

SnowCome (8 and 14 TB)
Snowball Edge (39,5 and 80TB)
Snowmobile (100PB) 

You can get several of them so virtually you could move Exabytes of information