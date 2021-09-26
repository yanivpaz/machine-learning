# Deep Lens 

## Reset 
https://docs.aws.amazon.com/deeplens/latest/dg/deeplens-troubleshooting-factory-reset.html
- on windows there is no need for gparted 
- download UNetbootin for windows 


## Post installation steps
- register the device in AWS deeplens
- update the device 
- connect to the device and view stream  
https://docs.aws.amazon.com/deeplens/latest/dg/deeplens-viewing-device-output-on-device.html  
```
mplayer -demuxer lavf /opt/awscam/out/ch1_out.h264  
```
- upload first model   
https://docs.aws.amazon.com/deeplens/latest/dg/deeplens-get-start-easy.html  


## Face recognition process 
https://aws.amazon.com/deeplens/community-projects/Family_Assistant/

### deployment phase 
https://github.com/ssolkhan/deeplens-challenge/blob/master/deeplens-face-detection-d90ecbd1-eeff-4ccd-abfa-0f4981e0525b/greengrassHelloWorld.py
