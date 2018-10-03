
* [EC2 & EBS cost](#ec2_ebs_cost)


#### ec2_ebs_cost 
  You are charged for `EBS` storage for the amount of storage provisioned to your account, measured in "gigabyte-months."
  `EC2` instances accrue charges only while they're running, but `EBS` volumes attached to instances continue to retain information and 
  accrue charges, even when the instance is stopped. To stop EBS-related charges, delete EBS volumes and EBS snapshots you don't need.
  
  **After you detach a volume, you are still charged for volume storage as long as the storage amount exceeds the limit of the AWS Free     Tier. You must delete a volume to avoid incurring further charges**
  
  For cost effectiveness, `EBS snapshots` are billed at a lower rate than active `EBS volumes` are. You can minimize your `EBS` charges but retain the information stored in `EBS` for later use by creating a snapshot of the volume as a backup and then deleting the active volume. Later, when you need the information stored in the snapshot, you can restore the `EBS volume` from the snapshot for use with your infrastructure.