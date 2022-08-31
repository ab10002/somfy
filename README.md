# Somfy plugin for Domoticz - Beta version


To install plugin
Then go in your Domoticz directory using a command line and open the plugins directory.
```
cd domoticz/plugins
git clone https://github.com/MadPatrick/somfy
git branch beta 
```
Restart Domoticz with 
```
sudo systemctl restart domoticz.
```

to update:
```
cd domoticz/plugins/somfy
git branch beta 
git pull
```

In the web UI, navigate to the Hardware page. In the hardware dropdown list there will be an entry called "Somfy Tahoma or Connexoon plugin".
