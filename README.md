## Ubiquiti UniFi SSH Commands:

### Login
`root / ubnt` or `ubnt / ubnt`

### Reboot
`Reboot`
    
### Reset AP to Factory Default
`syswrapper.sh restore-default`

### Manually Upgrade AP
`syswrapper.sh upgrade http://ip-of-controller:8080/dl/firmware/BZ2/2.3.8.1597/firmware.bin`
    
### Enter CLI
`mca-cli`
    
### Set Inform Server
`set-inform http://ip-of-controller:8080/inform`
