## Welcome to icipe HPC CLUSTER NODE
hpc01 is a cluster running centos 6.9 at icipe. The cluster contains Bioinformatic modules and analytics tools. The cluster is aimed at increasing computational power by offering computing resources for bioinformatic needs and use at icipe.

### Performance

The cluster has a capacity to handle heavy and light analysis. 

```markdown
# **Memory and uptime**


top - 12:46:15 up 42 days,  4:39,  6 users,  load average: 14.52, 15.28, 12.96
Tasks: 1464 total,   3 running, 1461 sleeping,   0 stopped,   0 zombie
Cpu(s): 20.5%us,  1.7%sy,  0.0%ni, 77.5%id,  0.2%wa,  0.0%hi,  0.0%si,  0.0%st
Mem:  264648888k total, 264103500k used,   545388k free,  1079368k buffers
Swap: 524287996k total,  1679480k used, 522608516k free, 154987468k cached

## **Account and Usage**
HPC users are not permitted to share their accounts with others. The user accounts are active for the duration of the research, with an additional period of one year depending on the user needs. 
A user with an icipe HPC account can access the cluster with the command:
ssh –X <username>@hpc01.icipe.org 
where “-X” is the flag for exporting the graphics with ssh. Users are strictly advised against sharing their access details with other users. The scheduler reserves available compute nodes and other resources on a first-come-first-served basis among Users with equal priority, but this does not apply to system administration and testing of the machine. NB: This is operational from November 2019. 
  
### **Data Storage and Backup**
  The users are responsible for ensuring a backup of their data exits. The HPC is intended to be used for data analysis, and the available storage space is geared towards just that. The unit provides support for long term data storage, specifically for raw data, which is the property of icipe (See Research Data Management and Archiving Policy).
The users are expected to provide detailed README with the following information:
- Project structure organization: General Organization of the project data
-  How was the data generated? Samples sourcing, preparation, and sequencing
-  A summary of the original use of the data, including research output such as publications
-  Link to GitHub repo containing scripts or pipelines used in data processing and analysis
-  Contact details
-  Funding acknowledgement (anyone reusing the data may be required to acknowledge funder)
-  Data in the HPC are retained for a year after the project is completed. After which only Data tagged for long term storage, which must have detailed documentation, are moved to cold storage. 
####**Running Jobs in the HPC**

Although jobs are currently being run in the login node, this is not the ideal. We are setting up a SLURM job management system for that purpose. From November 2019, we no longer accept jobs running on the login node; the system admin kills these without notice. You are, however, allowed to test scripts or compile code. 
Information on how to submit Jobs using the SLURM system is available from [jobs](htt)Familiarize yourself with these resources before using the HPC. 
  
#####**Bioinformatics Software**
  
The HPC makes use of a module system for managing bioinformatics software. You can check the available modules using `module avail`. Where software is missing, you can request for it using this [link](). Provide version information, a link to installation instructions, a summary of intended use, and any other information that would ease its setup.   


**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Account creation](https://redcap.icipe.org/surveys/?s=JAP78NN73C).
For more details see [HPC_POLICY](https://redcap.icipe.org/surveys/?s=JAP78NN73C).

