# PCBTAGS

PCBTAGS is a simple tool to create customized keychain sized name tags, spotify code, business card, with PCBs.

This tool exports a gerber file which should be ready for production by all major PCB factories.
The PCB generation is based on the KiCad software and the website allows you to export the .kicad_pcb file for you to make edits if you want to

The [server](https://github.com/TheStaticTurtle/pcbtags_server) and [frontend](https://github.com/TheStaticTurtle/pcbtags_frontend) for PCBTAGS are both open-source and licensed under GPLv3
allowing you to extend the capabilities of the projet by creating new generators.

Preview here: https://tags.thestaticturtle.fr/ (no promises of how long I'll keep it running)

## TODO
There are a few things that I would really like to get working if I get the motivation:
- [ ] Battling with kicad scripting api to add a 3D model to preview
- [ ] Adding patterns for the underside of the tags (maybe with an SVG import)
- [ ] Business card format for the nametags & spotify tags


## Screenshots
### Spotify tag
![image](https://user-images.githubusercontent.com/17061996/184560364-f0efdd65-3ff4-4919-b58f-3ee201071da8.png)
### Nametag
![image](https://data.thestaticturtle.fr/ShareX/2022/08/15/chrome_2022-08-15_02-20-27_a2064e7b-7df5-40fd-88f0-f4b0c2f39439.png)
