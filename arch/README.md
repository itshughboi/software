##### Verify UEFI x64
`cat /sys/firmware/efi/fw_platform_size` >> verify it is '64'

&nbsp;
#####  Add network

`ip link` >> shows network adapters
`iwctl` >> enter interactive mode
`device list` >> shows my adapters
`device wlan0 show` >> show properties of that network adapter
`station 'name' scan` >> name e.g. wlan0
`station 'name' get-networks` >> shows available wifi networks
`station 'name' connect SSID`

&nbsp;
##### Setup installer
`pacman -Syy` >> sync packages
`pacman -S archinstall` >> pulls updated interactive mode
`archinstall` >> enters interactive mode


##### Post-install test network
!! Once logged in, attempt to ping a FQDN like ping archlinux.org. If you have a problem (especially wifi) do the following

`nmcli device wifi connect SSID password "securepassword"`





***
### Hyprland
##### Clone Hyprland Repo
`git clone https://github.com/SolDoesTech/HyprV2.git`
`cd HyprV2`
`chmod +x set-hypr` >> makes it executable
`./set-hypr` >> run executable




