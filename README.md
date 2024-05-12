# Josh's homelab
This is my personal documentation of my homelab journey.  
Here you should find the notes, setups, apps, and videos/info I reference to learn.  
I also am using this to learn github as a platform.

# Current Setup
* Proxmox machine using a Ryzen 5 2600x, 16GB DDR4 RAM, 512GB SATA SSD, 1TB SATA HDD
  - Current Services:
    - [PiHole DNS](PiHole)
    - DuckDNS
    - Portainer
    - [GNS3](GNS3)
    - [Wireguard](Wireguard)
    - [Dashy](Dashy)
* TP-Link tl-sg105e 1GB 5 port managed switch
* TP-Link POE injector
* TP-Link EAP223
* Navepoint 12U rack

# Future Plans
- [ ] Organize my current homelab setup better
- [x] ~~Set up a dashboard ([Dashy?](https://dashy.to/)) for quick access all my services~~ (5/12/24)  
- [ ] Learn more about [Ansible](https://www.ansible.com/) and [Terraform](https://www.terraform.io/) and see if deploying them would be useful  
  - [ ] Learn YAML  
- [ ] [Ollama](https://ollama.com/library/llama3) seems interesting, but I'm unsure if I could reasonably run it 24/7 with my current resources  
- [ ] Get a larger (> 8 port) POE+ switch
  - [ ] Potentially move away from decentralized security and utilize a self-hosted NVR
- [ ] Create a NAS machine(s)
- [ ] Locally create SSL certificates for my services
