# 42_School_Born2beRoot  
  
## Summary  
This project focuses on system administration and introduces you to virtualization through the setup of a server using Debian. It involves following specific instructions to create a secure and functional environment while implementing best practices for system management.  
  
## Introduction  
The primary goal of this project was to gain hands-on experience in system administration, specifically through virtualization. I chose to use Debian as my operating system to set up my first server. By following strict guidelines and implementing necessary configurations, I was able to create a robust virtual machine that meets the project requirements.  
  
## Implementation Process  
  
### Choosing Debian
After reviewing the options, I opted for the latest stable version of Debian, as it is widely recommended for beginners in system administration. Debian's extensive documentation and community support provided an excellent resource for resolving any issues encountered during the project.  
  
### Virtualization Setup  
1. **Environment**: I used VirtualBox to create my virtual machine. This required downloading and installing VirtualBox on my local machine.  
2. **Configuration**: Following the guidelines provided in the [Born2beRoot Tutorial](https://github.com/gemartin99/Born2beroot-Tutorial/blob/main/README_EN.md), I configured my VM's resources, such as CPU and RAM, based on the project specifications.  
  
### Disk Partitioning and LVM  
I created at least two encrypted partitions using Logical Volume Manager (LVM). The partitioning scheme followed the example provided in the guidelines, ensuring that the server had the necessary structure for optimal performance and security.  
  
### Server Configuration
1. **SSH and Firewall**: I set up SSH on port 4242 and configured UFW to allow only this port. I also ensured that root login via SSH was disabled for security purposes.  
2. **User Management**: A new user was created with my login name, and I configured the system to comply with the strong password policy as outlined in the project guidelines.  
3. **Sudo Configuration**: Sudo was installed and configured to limit authentication attempts and log all actions in a designated directory.  
  
### Script Development  
I developed a monitoring script (`monitoring.sh`) in Bash to display system information at regular intervals. The script covers essential metrics, such as:  
- Architecture and kernel version  
- Number of physical and virtual processors  
- RAM and disk usage  
- CPU load and active connections  
- Last reboot time and user count  
  
### Final Touches  
After implementing all the mandatory components, I thoroughly tested the system to ensure everything functioned correctly. I also created a `signature.txt` file containing the signature of my virtual disk, as required for submission.  
  
## Conclusion  
The "Born2beRoot" project significantly enhanced my understanding of system administration and virtualization. Following the guidelines provided in the [tutorial](https://github.com/gemartin99/Born2beroot-Tutorial/blob/main/README_EN.md) was instrumental in successfully completing the project. I look forward to further enhancing my skills in system administration and exploring more complex configurations in future projects.  
  
## Acknowledgments  
Special thanks to the contributors of the [Born2beRoot Tutorial](https://github.com/gemartin99/Born2beroot-Tutorial/blob/main/README_EN.md) for their comprehensive guidance throughout this project.  
  