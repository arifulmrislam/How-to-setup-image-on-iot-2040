
# Project Title

iot2000setup

How to setup image on iot-2040:

1.download the image from sameness site,

	https://support.industry.siemens.com/cs/document/109741799/simatic-iot2020-iot2040-sd-card-example-image?dti=0&lc=en-US

2.Formate the sd card and download the image on SD card by bleacher.

    Update image version V2.6.1

After image setup flow this link: 

    HTTPs: //help.ubidots.com/en/articles/1785443-siemens-iot2040-setup-and-activation

Start node red:

	node /usr/lib/node/node-red/red
	or
	node /usr/lib/node_modules/node-red/red &

For node-red open by putty we must stop auto mode from setting.

**For solve the node download problem, visit this site:
    https://support.industry.siemens.com/tf/ww/en/posts/tip-installing-nodes-on-iot2000/180905/

Important note:

	1.If we update the new version of node-red on IoT-2040. It will be take new path which we have to find out by "WinSCP" application.
Like our node-red path is this 
    "node /usr/lib/node/node-red/red" 
but after update a new version it will be like this 
    "node /usr/lib/node_modules/node-red/red".
SO, we have to sure that where we install our new version.



## Authors

- [arifulmrislam](https://github.com/arifulmrislam)

  
## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ariful-islam-arif-2987b51a3/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/arifulislam301)

  
