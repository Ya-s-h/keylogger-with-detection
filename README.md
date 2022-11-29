# keylogger-with-detection
## Disclaimer:

Currently detection only works for Linux based OS
For windows we already have windows defender. 
For ease, use different terminal for detection and keylogger


For creating account on mailtrap.io, follow this: https://www.youtube.com/watch?t=70&v=fVJs-KK9xP0&feature=youtu.be\

## After setting up the account on mailtrap, copy your username and password and paste it in credential.py

###Steps to follow to run script:

For first time running:\
	1> pip install -r requirements.txt\
2> python detection.py\
3> python keylogger.py\
Both your terminal will look like this:\
  
![picture 1](/img/Picture1.png?raw=true)

After telling detector not to add the given process in whitelist, keylogger will abruptly stop.
 
  
![picture 2](/img/Picture2.png?raw=true)

 
If otherwise, keylogger will keep on running. ggwp
