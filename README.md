# Shell 01: Advanced Shell Commands and Data Processing
## Project Overview
Shell 01 focuses on advanced shell commands for file manipulation, data extraction, and text processing and teaches how to extract system information, search for specific files, count filesystem objects, retrieve network data, and handle special characters in filenames.
## Educational Objectives
This project aims to:
1) Develop proficiency with complex shell commands and pipelines
2) Teach practical text processing and data extraction techniques
3) Enhance understanding of file system navigation
4) Build skills in shell scripting for task automation
5) Demonstrate the power of combining simple commands to solve complex problems

## Key Concepts and Skills Demonstrated
1) Command Chaining and Pipelines: Using multiple commands in sequence to transform data
2) Text Processing and Filtering: Extracting, formatting, and manipulating text data
3) Regular Expressions: Finding patterns in text data
4) File System Navigation: Searching for files based on various criteria
5) System Information Extraction: Retrieving and formatting system data

## Exercise Breakdown
1) ex01: Creating a script to display all groups a specific user belongs to, with comma-separated output (cmds: id, tr)
2) ex02: Writing a command that finds all files with a .sh extension and displays their names without the extension (cmd: find)
3) ex03: Developing a script that counts all files and directories in the current directory and its subdirectories (cmds: find, wc)
4) ex04: Creating a command that displays all MAC addresses of the machine (cmds: ifconfig, grep, awk)
5) ex05: Learning to create a file with special characters in its name containing only "42"

## Technical Approach
This project employs:
1) Command Pipelines: Chaining multiple commands with pipes to process data in stages
2) Text Filtering: Using commands like grep, and awk to extract and manipulate text
3) Pattern Matching: Employing regular expressions for flexible text processing
4) Shell Script Logic: Creating scripts with practical utility
5) Command Output Redirection: Controlling where command output is sent

## Technologies Used
1) Shell: /bin/sh (Bourne shell)
2) Core Unix Commands: find, grep, tr, wc, etc.
3) Text Processing Tools: awk
4) System Information Commands: id, ifconfig, etc.

## Setup Instructions
Clone this repository:
git clone https://github.com/gtretiak/42School/blob/main/Piscine-2024/shell01
cd shell01
Each exercise is contained in its own directory (ex01, ex02, etc.)
Make all scripts executable:
chmod +x ex01/print_groups.sh ex02/find_sh.sh ex03/count_files.sh ex04/MAC.sh
To test specific exercises:
# For exercise 01 
Set environment variable first
For example, export FT_USER=yourusername
./ex01/print_groups.sh

# For exercise 02
./ex02/find_sh.sh
Create as many .sh files as you want, as deep in a directory as you want - it's going to find it.
# For exercise 03
./ex03/count_files.sh
., .. - are already two! Add more and see how the output is changed.

# For exercise 04
./ex04/MAC.sh
# For exercise 05
Try to create your own

## Practical Real-World Applications
1. Automated Security Auditing
System administrators can use scripts similar to print_groups.sh to audit user permissions across multiple servers, identifying potential security risks where users have excessive access privileges
Security teams can check for unauthorized users in privileged groups using similar techniques adapted to their needs

2. DevOps Workflow Optimization
DevOps engineers can create scripts, similar to find_sh.sh, to find specific configuration files across complex infrastructure
Similar file-finding techniques may be used to identify which files have changed and require testing or deployment
Build systems can efficiently process only relevant source files based on pattern matching, significantly improving compilation times

3. Storage Management and Optimization
Like count_files.sh, storage administrators can identify certain directories with excessive file growth causing space issues

4. Network Security and Device Management
Security teams can use techniques from MAC.sh to inventory all network devices and detect unauthorized equipment
Network administrators can use MAC address tracking to implement and verify access control policies
During security incidents, identifying all network interfaces assists in containing potential breaches

5. Log Analysis and System Troubleshooting
System troubleshooters use similar text processing techniques to parse large log files and identify error patterns
Administrators can create automated alerts based on specific patterns appearing in system logs, enabling proactive issue resolution

Each of these applications represents how the seemingly simple commands learned in Shell 01 form the building blocks of sophisticated automation, monitoring, and management systems used throughout enterprise technology environments today.

## Conclusion
Shell 01 represents a crucial stepping stone in developing the command-line proficiency that underpins modern system administration, DevOps practices, and software development workflows. The skills acquired in this project—combining simple commands into powerful pipelines, extracting specific data from system information, and automating repetitive tasks—form the foundation for more advanced automation and scripting capabilities.
What makes these skills particularly valuable is their universal applicability across different technical domains. Whether working with cloud infrastructure, containerized applications, large-scale data processing, or security analysis, the effective command-line solutions are quite useful.
