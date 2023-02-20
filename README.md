## Ubiquiti UniFi SSH Commands:

### Login
`root / ubnt` or `ubnt / ubnt`

### Reboot
`Reboot`
    
### Reset AP to Factory Default
Before and after v2.2.x - `syswrapper.sh restore-default`
After v2.2.x - `set-default`

### Manually Upgrade AP
`syswrapper.sh upgrade http://ip-of-controller:8080/dl/firmware/BZ2/2.3.8.1597/firmware.bin`
    
### Enter CLI
`mca-cli`
    
### Set Inform Server
`set-inform http://ip-of-controller:8080/inform`
