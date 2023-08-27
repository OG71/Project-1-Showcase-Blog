# Project-1-Showcase-Blog
First project from UT Austin Cybersecurity Bootcamp. Custom web application deployed via Azure web applications. 

Unfortunately, because Azure cloud services are not free, I've had to take down the website. With that being said, this repository serves as a showcase in it's abscense. 

# Step 1

First, a docker container was deployed via Azure Web Apps then the HTML was manually configured to display what's seen on the screen! While the website was active, the LinkedIn redirect and the email link were active as well. 

# Step 2 

Secondly, a keyvault was generated and a self-signed certificate was assigned to the domain. Because the Azure host is already certified, this was redundant; however, for the sake of experience, the certificate was assigned anyhow. 

# Step 3 

Finally, the application was properly secured using Azure Front Door. After, a web application firewall was implemented and attached to the network. Lastly, Azure Security Center recommendations were considered and implemented, if needed. 
