# nextcloud_pi4_compose
Raspberry Pi 4でNextCloudを建てるためのDockerComposeファイルです。  
portainer.io用に定義ファイルのバージョンを2にしています。  
ポートは8080を使用します。  

### Tested with following environment.
- Raspberry Pi 4B (4GB)
- Raspbian Buster Lite
- OpenMediaVault(port 80)
- Portainer.io(port 9000)

### How to
1. Access to portainer.io on your Raspberry Pi(ex. http://raspberrypi.local:9000)  
1. Select Endpoint(Docker)  
1. Stacks->+ Add Stack->Name as "nextcloud"->Use a git repository->[input URL of this repo]->Deploy the stack
1. Wait for a while...
1. Access to nextcloud on your Raspberry Pi(ex. http://raspberrypi.local:8080)   
  Android smartphone is not compatible due to mDNS(Bonjour) required.  
1. Enjoy!

