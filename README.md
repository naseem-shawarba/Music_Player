# Music Player
Welcome to the Music Player Website! This platform allows users to search for, discover, and play music effortlessly. Dive into your favorite tracks, explore new tunes, and enjoy songs from specific artists with our intuitive and user-friendly interface.
## Frameworks Used
* React.js
* Tailwind CSS
* Redux
* JavaScipt

## Screenshots

![Screenshot1](https://github.com/naseem-shawarba/Projects_Screenshots/blob/main/Music_Player/Screenshot1.png)


## Getting Started

If you want to clone the repo and run the app locally, you need to obtain two API keys.

The first one is from <a href="https://rapidapi.com/WaveTech/api/shazam-core7">Shazam Core</a>. After obtaining the key, create a file named .env in the root directory of the project and add the API key within double quotes as follows:
```bash
VITE_SHAZAM_CORE_RAPID_API_KEY="<KEYGOESHERE>"
```
The second one is from <a href="https://geo.ipify.org/">Geo Ipify</a>. After obtaining the key, add the key to the .env file in the root directory of the project and add the API key within double quotes as follows:
```bash
VITE_GEO_API_KEY="<KEYGOESHERE>"
```

After setting up the .env file, you can use the following commands to run the app in development mode or build the app for production:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
