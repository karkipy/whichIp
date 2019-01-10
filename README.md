## Which Ip
  A simple bash script to find ip

## Motivation

Working in react-native, you may have multiple devices and the host for the device would be running in another side or the device you work on, usually the ip address while working locally won't be changed but who knows. So a simple script to find ip rather than the big spaghetti output of
```bash
  ifconfig en0
```

## Installation

Manual

```bash
  git clone {this-repo}
```

Give the permission to the script

```bash
  chmod +x whichIp
```

Move the script to /usr/local/bin for global access

```bash
 mv whichIp  /usr/local/bin
```

### or

This does all the things above

```bash
curl https://raw.githubusercontent.com/karkipy/whichIp/master/whichIp -o /usr/local/bin/whichIp && chmod +x /usr/local/bin/whichIp
```



Restart the terminal

### Output

<img width="399" alt="screen shot 2019-01-10 at 12 07 47 pm" src="https://user-images.githubusercontent.com/12614476/50949967-70d0dc80-14d0-11e9-985c-a29baf213cc2.png">


