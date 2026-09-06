```
 ▄█     █▄   ▄█   ▄█       ████████▄     ▄████████    ▄████████ ▀████    ▐████▀ 
███     ███ ███  ███       ███   ▀███   ███    ███   ███    ███   ███▌   ████▀  
███     ███ ███▌ ███       ███    ███   ███    █▀    ███    ███    ███  ▐███    
███     ███ ███▌ ███       ███    ███  ▄███▄▄▄       ███    ███    ▀███▄███▀    
███     ███ ███▌ ███       ███    ███ ▀▀███▀▀▀     ▀███████████    ████▀██▄     
███     ███ ███  ███       ███    ███   ███    █▄    ███    ███   ▐███  ▀███    
███ ▄█▄ ███ ███  ███▌    ▄ ███   ▄███   ███    ███   ███    ███  ▄███     ███▄  
 ▀███▀███▀  █▀   █████▄▄██ ████████▀    ██████████   ███    █▀  ████       ███▄ 
                 ▀                                                              
```

> **Francol Steven Aristizabal Romero** · Medellín, Colombia  
> Co-founder at Mood Studios LLC. Game designer, UX and UI designer, and I build the apps I want to exist.

I came up through digital art and game design, and that is still the centre. I care how
an interface feels to use: the look, the interaction, the details nobody notices until
they are wrong. The projects below are apps I wanted to exist, so I made them. When one
needs a server or a deploy pipeline I build that too, because the app needs it, not
because it is the point.

Colombian, self-taught, still learning in public.

---

## Currently building

### Splitwars Online
Sci-fi isometric MMO RTS for PC and mobile, in closed alpha. A Unity 6000.3 client talks
to a Java backend on SmartFoxServer, with a Go load balancer and fleet observer in front,
a Rust pipeline that builds and packages client releases, and a Cloudflare Worker serving
the development CDN. Payments go through Xsolla.

[splitwars.com](https://splitwars.com)

### Arena Assistant
Companion app for the League of Legends Arena mode. Electron and React on the desktop,
backed by a Node and Express crawler that has pulled 1.8M matches and 35M participant
rows into Postgres and aggregates them on a 15 minute cycle. Releases go out as blue/green
Docker swaps behind nginx from GitHub Actions, and the Windows installer is code-signed
with auto-updates through electron-updater.

[arena-assistant.com](https://arena-assistant.com)

### Sweepr98
Minesweeper rebuilt for the browser inside a Windows 98 shell, with co-op, race, and
ranked modes. Solo build, start to finish.

[sweepr98.com](https://sweepr98.com)

### Mood Collab
Real-time Markdown collaboration for Obsidian. Per-user cursors, anchored comments,
folder-level roles for editors and viewers, and conflict-safe reconciliation for notes
that changed on disk while you were offline.

[Listing and releases](https://github.com/MoodStudios/moodstudios-collab-dist)

### Pharmacy POS and ERP
Replacing a legacy .NET point-of-sale and ERP for a pharmacy business. Java backend, two
TypeScript frontends (a stripped-down counter POS and a full backoffice that ships as both
web and a Tauri desktop app), both drawing on one shared design system.

---

## Open source

- [nextclaim](https://github.com/Wildeax/nextclaim). Electron tray app that auto-claims the daily free games on Epic, Prime Gaming, and GOG.
- [Questionary](https://github.com/Wildeax/Questionary). React quiz app that loads questions from JSON or YAML, randomizes order, and resumes an unfinished session.
- [aroma-affect](https://github.com/MoodStudios/aroma-affect). Minecraft mod that gives the player a sense of smell.

---

## Stack

**Languages and runtime**

<img src="https://skillicons.dev/icons?i=ts,js,cs,java,go,rust,lua,nodejs" height="42" alt="TypeScript, JavaScript, C#, Java, Go, Rust, Lua, Node.js" />

**Apps and interfaces**

<img src="https://skillicons.dev/icons?i=react,electron,tauri,tailwind,vite,unity" height="42" alt="React, Electron, Tauri, Tailwind, Vite, Unity" />

**Data and infrastructure**

<img src="https://skillicons.dev/icons?i=postgres,redis,sqlite,docker,nginx,cloudflare,githubactions" height="42" alt="Postgres, Redis, SQLite, Docker, nginx, Cloudflare, GitHub Actions" />

**Design and art**

<img src="https://skillicons.dev/icons?i=blender,figma,ps,ai" height="42" alt="Blender, Figma, Photoshop, Illustrator" />

The art side has not gone anywhere. Cyberpunk and retro-futurist illustration, UI work,
and 3D still feed everything above, they just live on Instagram instead of in this repo list.

---

## Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Wildeax&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=00000000&title_color=FF2E88&icon_color=00E5CF&text_color=9BA5B4&ring_color=FF2E88" height="165" alt="GitHub stats" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Wildeax/wildeax/output/snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/Wildeax/wildeax/output/snake.svg" alt="Contribution graph being eaten by a snake" />
</picture>

</div>

---

## Elsewhere

<div align="center">

<a href="https://wildeax.com"><img src="https://img.shields.io/badge/wildeax.com-0D1117?style=for-the-badge&logo=firefoxbrowser&logoColor=FF2E88" alt="wildeax.com" /></a>
<a href="https://www.linkedin.com/in/wildeax/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://x.com/Wildeax_"><img src="https://img.shields.io/badge/@Wildeax__-0D1117?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
<a href="https://instagram.com/wildeaxart/"><img src="https://img.shields.io/badge/@wildeaxart-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
<img src="https://img.shields.io/badge/Discord-wildeax-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord: wildeax" />

</div>
