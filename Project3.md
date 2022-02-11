STEP 1- BACKEND CONFIGURATION

First, I updated and upgraded the Ubuntu server to the latest version with the following commands:

`sudo apt update`

`sudo apt upgrade`

![Image1a](./Images/Image1a.PNG)

![Image2a](./Images/image2a.PNG)

The code below was used to get the location of Node.js software from Ubuntu repositories:

`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -`

![Image3a](./Images/Image3a.PNG)

![Image3b](./Images/Image3b.PNG)

Installed Node.js on the server using the code below. This command also installs npm:

`sudo apt-get install -y nodejs`

![Image4](./Images/Image4.PNG)

The node installation (node.js and npm) was  verified by running the codes below:

`node -v `

`npm -v `

![Image5](./Images/Image5.PNG)

I created a new directory named "todo" then ran a command to verify the directory was created and then changed from my current directory into the nwely created "todo" directory:

`mkdir Todo `

`ls `

`cd Todo`

![Image6](./Images/Image6.PNG)

