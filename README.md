TASK - 2: CLOUD MONITORING AND ALERTS

COMPANY: CODTECH IT SOLUTION 
NAME: V. MADHUMITHA 
INTERN ID: CITSOD393 
DOMAIN: CLOUD COMPUTING
DURATION: 4 WEEKS 
MENTOR: NEELA SANTOSH


Objective:

Set up monitoring and alerts for a cloud-based application using AWS CloudWatch.


-> Steps:
-> 1. Created CloudWatch Dashboard

A custom dashboard was created to monitor the following EC2 instance metrics:

* CPUCreditBalance
* CPUUtilization
* DiskWriteOps
* NetworkPacketsIn
* NetworkIn


-> 2. Created Alarm for CPU Utilization

An alarm named HighCPUUtilizationAlarm was configured to trigger when:

> CPUUtilization > 80% for 1 datapoint within 5 minutes



-> 3.Configured Alarm Actions

* SNS Topic was created and notification email added.
* Actions were configured to notify when alarm state is In alarm.
* Actions enabled


-> 4.Final Alarm Status

Successfully created and confirmed alarm setup with:

* State: OK (when CPU is normal)
* Actions: Enabled
* Email subscription pending → confirmed later manually


-> Tools Used

* AWS CloudWatch
* Amazon SNS
* EC2 Instance


-> Future Enhancements

* Configure additional alarms for memory, disk I/O, and network out.
* Automate recovery actions using Auto Scaling or Lambda.
* Set up alerts across multiple regions for failover coverage.



->OUTPUT

<img width="1233" height="767" alt="Image" src="https://github.com/user-attachments/assets/886fe946-9f8c-4730-9dbe-78e35cfcd3d0" />

<img width="1580" height="306" alt="Image" src="https://github.com/user-attachments/assets/92574368-93e7-4c6d-8e13-fb9ac97a2ef9" />

<img width="981" height="856" alt="Image" src="https://github.com/user-attachments/assets/46990d8c-0b34-43d6-bf23-1c8a983d38ae" />

<img width="1554" height="384" alt="Image" src="https://github.com/user-attachments/assets/48fc2333-0db3-4a84-a086-c8037d887927" />



