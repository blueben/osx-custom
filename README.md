osx-custom
==========

Customizations for OS X workstations

### Disable atime

Drop com.custom.noatime.plist in /Library/LaunchAgents/ and then load it using launchctl.

```sudo launchctl load -w /Library/LaunchAgents/com.custom.noatime.plist```

### Disable the Sudden Motion Sensor

Run the pmset command in disable_sms.pmset

### Disable system hibernation

Run the pmset command in disable_hibernation.pmset
