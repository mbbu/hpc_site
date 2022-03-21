ICIPE Research Computing
##  Icipe Reasearch Computing
This is the Icipe Research Computing Resource. Here you'll find information about the research computing infrastructure, including information about [Software](https://github.com/mbbu/Icipe-hpc-environment), help using SLURM, etc.

### Performance

There are two worker clusters hpc01 and hpc02  with a single controller node.The clusters use a job scheduler mechanism to manage and handle workloads.
The cluster is arranged in a master/slave configuration; users log into HPC (the log-in) and use it as a "jumping off point" to the rest of the cluster.

```markdown
# 

| Machine       | Specification   |Uses   |
| :------------ |:---------------:| -----:|
| HPC           | 8GB RAM,5       | NO workloads |
| HPC01         | 64GB RAM,       |   Heavy workloads |
| HPC02         | 64GB RAM,       |    Heavy workloads |

```


# Account and Usage
HPC users are not permitted to share their accounts with others. The user accounts are active for the duration of the research, with an additional period of one year depending on the user needs.

Connecting to the HPC is not done through ssh connection In order to launch computations on the HPC or even just to view files residing in its storage infrastructure, users must use the SSH protocol. Through this protocol, users gain command-line access to the HPC from an SSH client software installed on their own machine (e.g. a laptop, desktop or smartphone). Depending on the operating system you are using on the computer from which you want to establish the connection, the procedure differs:

  # If you are running Mac OS X (on Apple computers) or any GNU/Linux distribution
        Most of these operating systems are unix based which come with ssh protocol already installed.Just open your terminal and `ssh user@hpc01.icipe.org`then enter your password. If that does not work install ssh client based on your operating system. Connecting to the server requires access through icipe internal network or access to icipe Vpn.

   # If you are running Windows
    For windows users you will have to install [openssh](https://www.openssh.com).Another option is to install [mob-xterm](https://mobaxterm.mobatek.net/download-home-edition.html)
             - host: hpc.icipe.org 
             - port: leave the default SSH port, i.e. port 22
             - username: your username, as communicated by the person who created your HPC account.

# Data Storage and Backup 
  The users are responsible for ensuring a backup of their data exits. 
  The HPC is intended to be used for data analysis, and the available storage space is geared towards just that. 
  The unit provides support for long term data storage, specifically for raw data, which is the property of icipe (See Research Data Management and Archiving Policy).

# Running Jobs in the HPC

A We are setting up a SLURM job management system for that purpose.
We no longer accept jobs running on the login node; the system admin kills these without notice. You are, however, allowed to test scripts or compile code. 

  
# Bioinformatics Software
  
The HPC makes use of a module system for managing bioinformatics software.
You can check the available modules using `module avail`. 
Where software is missing, you can request for it . 
Provide version information, a link to installation instructions, a summary of intended use, and any other information that would ease its setup.   





For more details see [Account creation](https://redcap.icipe.org/surveys/?s=JAP78NN73C).
For more details see [HPC_POLICY](https://redcap.icipe.org/surveys/?s=ENEFCLFTME).

