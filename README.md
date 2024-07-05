# AirCap Tool For Hunting WPA Handshake and DoS Deauth

AirCap is a powerful tool designed for hunting WPA handshakes and performing DoS deauthentication attacks. It allows users to capture WPA handshakes, perform DoS attacks, and save the captured data for further analysis.

## Features

- Capture WPA handshakes.
- Perform DoS deauthentication attacks.
- Save captured handshakes to a file.
- Works with specified wireless interfaces, channels, and BSSIDs.
- Optional client-specific deauthentication.

## Usage

```sh

 █████╗ ██╗██████╗      ██████╗ █████╗ ██████╗
██╔══██╗██║██╔══██╗    ██╔════╝██╔══██╗██╔══██╗
███████║██║██████╔╝    ██║     ███████║██████╔╝
██╔══██║██║██╔══██╗    ██║     ██╔══██║██╔═══╝
██║  ██║██║██║  ██║    ╚██████╗██║  ██║██║
╚═╝  ╚═╝╚═╝╚═╝  ╚═╝     ╚═════╝╚═╝  ╚═╝╚═╝

[+] AirCap Tool Made By Eslam Mohamed <Sysc4ll3r> To Capture WPA Handshake and PMKID
[+] github: https://github.com/Sysc4ll3r

[+] Usage:

-i|--interface|-iface <wireless interface> , [Needed]
-ch|--channel|-chan <channel of accesspoint> , [Needed]
-b|--bssid <bssid of accesspoint> , [Needed]
-dc|--deauth-count|-count <number of deauth times , Default=0 mean infinity > , [Optional]
-c|--client|-client <client macaddress> , [Optional]
-f|--file|-file <filename to write the handshake> , [Optional]
-dos|--dos|-x , this flag means to make a DOS deauth attack & capture handshake  [Optional]
```


To use AirCap, you need to run it with specific arguments as described below:

```sh
./aircap -i <wireless interface> -ch <channel of accesspoint> -b <bssid of accesspoint> [options]
```


