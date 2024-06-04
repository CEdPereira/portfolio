# portfolio
My portfolio repository at GitHub.
Welcome to my Cybersecurity Projects Portfolio! Here, I showcase projects that I've been involved in to develop the hard skills necessary to contribute to the cybersecurity field.

Projects

1. File permissions in Linux

■ A group of researchers share a common directory that requires specific permissions for users, groups and others. The analyst job was to check the permissions for all files in the directory, including any hidden files, to make sure that permissions align with clearance. All permissions must match clearance to minimize risks, otherwise they were changed to meet demands.  

<img width="697" alt="Screenshot 2024-06-04 at 4 47 12 PM" src="https://github.com/CEdPereira/portfolio/assets/171424243/c747199f-77fc-4b6a-8ad4-997fb5b480cb">

We first removed others writing permissions so that they could only have reading permissions to mitigate risk.  

<img width="660" alt="Screenshot 2024-06-04 at 5 00 20 PM" src="https://github.com/CEdPereira/portfolio/assets/171424243/5ac17306-f95e-4721-8bc8-590e8ef4b704">    

Next, the file project_m.txt is a restricted file and should not be readable or writable by the group or other; only the user should have these permissions on this file. The security assistant listed the contents and permissions of the current directory, checked if the group has read or write permissions. The assistant then revoked the group’s reading permission.  

<img width="645" alt="Screenshot 2024-06-04 at 5 23 17 PM" src="https://github.com/CEdPereira/portfolio/assets/171424243/ea479f2f-90a1-4f0f-a17f-991511200156">

The file .project_x.txt is a hidden file that has been archived and should not be written to by anyone, although the user and group should still be able to read this file.  

<img width="653" alt="Screenshot 2024-06-04 at 5 02 16 PM" src="https://github.com/CEdPereira/portfolio/assets/171424243/85d67053-8dd3-4b0b-b345-c547c6ed265d">  

The analyst later revoked writing permission from the the user and group, then granted reading permission to the research team.

<img width="647" alt="Screenshot 2024-06-04 at 5 06 19 PM" src="https://github.com/CEdPereira/portfolio/assets/171424243/a337c497-a5d3-480e-9426-c7e61d2a74bb">  

Only the researcher2 user should be allowed to access the drafts directory and its contents. This means that only researcher2 should have execute privileges. So the Analyst revoked group execute permission.  

<img width="642" alt="Screenshot 2024-06-04 at 5 41 49 PM" src="https://github.com/CEdPereira/portfolio/assets/171424243/652b3afb-9596-4af8-836e-6b3751597459">  
<img width="646" alt="Screenshot 2024-06-04 at 5 42 14 PM" src="https://github.com/CEdPereira/portfolio/assets/171424243/3535ecda-673d-4581-b2e8-a47e68eb452f">  

■ Modeling and Evaluation: Permissions are granted for three different types of owners, namely user (researcher_2), group (research_group), and others using the system. Other users can have reading permissions for some files but no writing permissions. The file project_m.txt is a restricted file and should not be readable or writable by the group or other; only the user should have these permissions on this file. And the file .project_x.txt is a hidden file that has been archived and should not be written to by anyone, although the user and group should still be able to read this file.  

■ Conclusion: The security analyst provided an overview of files, hidden files  and directories within the system that required adjustments to their permissions to ensure appropriate clearance levels for users, groups, and others. The analysis identifies instances where current permission settings may pose security risks or violate organizational policies. By addressing these issues, the actions taken and report aims to enhance the overall security posture of the system to mitigate potential vulnerabilities. The recommendations outlined in the report emphasizes the importance of aligning permissions with the principle of least privilege, ensuring that access rights are granted only to those who require them for legitimate purposes. Additionally, the report highlights the need for ongoing monitoring and maintenance of permissions to adapt to evolving security requirements and minimize the risk of unauthorized access or data breaches.  
