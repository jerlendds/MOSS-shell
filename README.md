# Evergreen MOSS shell

An evergreen **M**odular **O**verlay **S**hell **S**ystem built with [quickshell](https://quickshell.org/) that I use as my desktop environment. TODO: Release later...

## Preview

[demo.mp4](https://github.com/user-attachments/assets/7764dd66-de8f-47cf-8263-bba37901385f)

## Features

<!--  Me + AI manually vetted the code at this last hash: https://github.com/roman-16/proton-cli/commit/97f80d65f6862eaa13cca225e301f08cbceb51c3 ~ looks legit, no malware :). I can not vouch for any newer commits at this time... -->
- Calendar          ~ Integrated with [Proton Calendar](https://calendar.proton.me) via [Roman-16](https://github.com/roman-16/)'s wonderful [proton-cli](https://github.com/roman-16/proton-cli) 
- Agents            ~ [LM Studio](https://lmstudio.ai/)
- Coding Analytics  ~ [wakapi](https://github.com/muety/wakapi) + [codex-wakatime](https://github.com/angristan/codex-wakatime)
- Clipboard History ~ [cliphist](https://github.com/sentriz/cliphist.git)
- Password manager  ~ [KeepassXC](https://github.com/keepassxreboot/keepassxc)
- Weather           ~ [Open-Meteo](https://open-meteo.com/)
- Github Traffic+Github Release Download stats panel
- Markdown Note Editor
- App launcher
- etc

<!-- TODO:
- Email ~ Integrated with [Proton Email](https://mail.proton.me) via [proton-cli](https://github.com/roman-16/proton-cli)
- File search (todo: find files indexer)
- Photo/image search (todo: build photos indexer that captions images via qwen3-vl-8b for search)
- Agent FS Organizer
- Github Traffic Analytics
- Power button (sleep, reboot, etc)
- Executeable codeblocks in markdown playbooks? 
- Pomodoro timer

 -->
- 

<!-- ## Prerequisites


#c Wonder why they called it wl-clipboard (wayland), works on the superior X11 system too, hmph 
```bash
sudo pacman -S xdg-utils wl-clipboard github-cli

# Configuring github traffic analytics...
gh auth login

#TODO cp systemd unit files over in this script...

systemctl --user daemon-reload
systemctl --user enable --now github-traffic.timer
systemctl --user list-timers github-traffic.timer

``` -->


<!-- 


TODO: also backup systemd/user files...

TODO: 

/home/jerlendds/.config/systemd/user/default.target.wants/greyproxy.service' → '/home/jerlendds/.config/systemd/user/greyproxy.service


 -->