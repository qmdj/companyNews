ThoughtWorks Homework

Basic problem
You need to create one environment for local QA.
Assumptions
• You have free rein to incorporate any software tools and hardware you need to
streamline application deployment and infrastructure provisioning &
configuration as long as they are Free/Libre/Open Source software (FLOSS). We
request that you use Linux.
• The development team has a continuous integration build that produces two
artifacts:
o a .zip file with the image and stylesheet used for the application
o a .war file with the dynamic parts of the application
• You should deploy the static assets to a web server and the .war file to a separate
application server. Any compatible servers are acceptable.
• The app (companyNews) uses Prevayler for persistence. Prevayler essentially
persists data to a file. The dev team chose this to simplify the development effort,
rather than having to deal with an RDBMS.
Expected output for this problem
Simply put, we want you to design and create the local QA environment. You should use
a virtualization solution such as VirtualBox for these environments. We do not want you
to deliver the VMs to us. Instead you should provide scripts/documentation to enable us
to build the environment ourselves very easily. We will use VirtualBox, VMWare or
EC2 (your choice) to build your environment. (If you have another virtualization solution
you would like to use please ping us first).
You are expected to deliver the following within 1 week:
• Write script or using DevOps tools to build local QA environment, you can use
Shell, Python, Puppet, Chef.
• Design a publish strategy integrating existing CI build and implement using script
or DevOps tools
