# SCA Cloud School Application
 Step 1
 Locate the folder with the dockerfile using command line. Then run the docker build command to build an image from the docker file as such below:
 dokcer build -t image-name .
 Step 2 
 Use the docker run command to create a writeable container layer over the specified image as such below:
 docker run -d image-name
 Step 3 Check the IP address where the container created is located using the docker exec command such as below:
 docker exec container-name powershell.exe ipconfig
 This shows you the IPv4 address that the webpage runs on for viewing.
 
