# vue-general-additions-to-boilerplate
Just some helpful things to drop in to new projects made using vite's creation boilerplate


jsconfig: starter includes making sure VSCode looks in src folder, and effective aliasing of @/ to /src/ for VSCode. Also sets baseURL

Additional:

"compilerOptions": {
    "module": "esnext",
    "target": "esnext"
  },

"compilerOptions": {
  "allowSyntheticDefaultImports": true
  },


vite.config.js: starter provides alias of @/ to src/