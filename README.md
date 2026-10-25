# FANGUYSS — PROFILE.OS v6.9.0

A cinematic, command-driven personal portfolio built with Next.js, TypeScript, React, Tailwind CSS, Framer Motion, Lanyard, and the browser Audio API.

## What it does

- Interactive terminal navigation
- Case-insensitive commands + aliases
- Command history and TAB autocomplete
- Live Discord presence through Lanyard
- Local MP3 music player with queue controls
- Theme switching and subtle ambient effects
- Responsive desktop/mobile experience
- GitHub/social navigation
- Accessibility and reduced-motion support

## Run locally

```bash
npm install
npm run dev
```

Then open `http://localhost:3000`.

## Production

```bash
npm run typecheck
npm run build
npm start
```

Deploy directly to Vercel. Set the variables from `.env.example` in the deployment environment. A GitHub token is optional.

## Local music

Put audio files in `public/music/` and matching artwork in `public/music/artwork/`. See `public/music/README.md`.

Spotify is not required for playback. Lanyard may still show a Discord user's Spotify activity when Discord exposes it.

## Commands

`help` `about` `whoami` `projects` `skills` `stack` `experience` `contact` `socials` `discord` `github` `status` `neofetch` `history` `date` `pwd` `ls` `open` `visit` `music` `nowplaying` `play` `pause` `resume` `next` `previous` `theme` `matrix` `coffee` `fortune` `ascii` `secret` `sudo` `konami` `42`

## Identity

**FANGUYSS** — Independent engineer crafting web products, internal tools, and the quiet infrastructure that keeps them alive at 3am.

GitHub: https://github.com/FANGUYSS

Website: https://fanguyss.me
