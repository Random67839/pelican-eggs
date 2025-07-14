## Teamspeak 6

### Read before installation!
This is a installation egg for [Pelican](https://pelican.dev) -gamepanel. If you are looking for solution for something else, you may experience if you want to; if it doesn't work you are on your own... and if this installation does not work you are also on your own.

Teamspeak 6 ARM64 installation egg is based on [teamspeak_ARM64](https://github.com/pelican-eggs/eggs/tree/master/voice_servers/teamspeak_ARM64) installation.

Please read more frequent information from [teamspeak/teamspeak6-server](https://github.com/teamspeak/teamspeak6-server) -repository.

## Server Ports

Ports required to run the server in a table format. Some ports are optional, you can use them if you desire.

| Port    | default | required|
|---------|---------|---------|
| Voice   | 9987    |yes      |   
| Query HTTP  | 10080   |no       |
| Query HTTPS  | 10443   |no       |
| Query SSH  | 10022   |no       |
| File transfer   | 30033   |no       |

## Server config

You can see server config and variables from [teamspeak/teamspeak6-server/CONFIG.md](https://github.com/teamspeak/teamspeak6-server/blob/main/CONFIG.md).

### ARM64
* The arm64 may not perform as expected due to the amd64 to arm emulaton. Server tested with Hetzner ARM 2vcore -vps with avg. puzzle precompute time ~2000ms and with Raspberry Pi 4B 2GB ~5500ms.

### Warranty 
No support shall be provided, you may fork eggs if something does not work or if you desire.
