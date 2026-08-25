# Evergreen MOSS shell

An evergreen **M**odular **O**verlay **S**hell **S**ystem built with [quickshell](https://quickshell.org/) that I use as my desktop environment. TODO: Release later...

## Preview

[demo.mp4](https://github.com/user-attachments/assets/7764dd66-de8f-47cf-8263-bba37901385f)

## Features

<!--  Me + AI manually vetted the code at this last hash: https://github.com/roman-16/proton-cli/commit/97f80d65f6862eaa13cca225e301f08cbceb51c3 ~ looks legit, no malware :). I can not vouch for any newer commits at this time... -->


| Feature | Description | Requirments |
|------------|-------------|----------|
| Agents | TODO: work-in-progress | [LM Studio](https://lmstudio.ai/) |
| App launcher | Top left bar ropdown menu for searching and starting your desktop apps |  |
| Calendar  | [Proton Calendar](https://calendar.proton.me) authenticated via your Proton account through [Roman-16](https://github.com/roman-16/)'s wonderful `proton-cli` | [proton-cli](https://github.com/roman-16/proton-cli)  |
| Coding analytics | Wakapi-inspired dashboard that connects directly to a local wakapi sqlite file | [wakapi](https://github.com/muety/wakapi) + [codex-wakatime](https://github.com/angristan/codex-wakatime) |
| Clipboard history | Copy old clipboard text and images from the past | [cliphist](https://github.com/sentriz/cliphist.git) |
| Password manager | Copy TOTP tokens and passwords from keepasscx files | [KeepassXC](https://github.com/keepassxreboot/keepassxc) |
| Weather | View the weather for your city | [Open-Meteo](https://open-meteo.com/) |
| Github traffic/release Downloads | Stats for OSS devs | [Github CLI](https://cli.github.com/) |
| Markdown editor | Codemirror [facets inspired architecture](.config/quickshell/markdown/README.md) md editor with a graph view | --- |
| Screen recorder  | Record a monitor and edit the video files through a notification menu | [ffmpeg](https://ffmpeg.org/) |
| Projects launcher | A repo list to open anything in the ~/Projects directory with `vscodium` | |
| Volume OSD sliders | Control master or per-app volume levels | |
| System metrics for RAM/CPU and the top processes | View your system utilziation metrics | |
| Flameshot screenshots with post-screenshot editing via Pinta | $mod+Shift+s | [pinta](https://www.pinta-project.com/) + [Flameshot](https://flameshot.org/) |
| Bottom notifications bar | TODO: View past notifications and with a subtle animation for new notifications | |
| $mod-tab i3 workspace switching | TODO... | |
| File indexer/file search | TODO... | |
| Image indexer/AI captions/image search | TODO... | |


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

<!-- ## Prerequisites


# Wonder why we need wl-clipboard (wayland), cliphist with wl-clipboard works on the superior X11 system too despite no wl-clipboard commands working, hmph 
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