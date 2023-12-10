# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

## configuracion de prettier

Agregar la siguente configuracion

```
  yarn add --dev prettier prettier-plugin-astro
```

Luego en el user setting de vscode, (settings.json) configurar

```
  "files.associations": {
    "*.astro": "astro"
  },
  "editor.formatOnSave": true,
  "prettier.documentSelectors": ["**/*.astro"],
  "[astro]": {
    "editor.defaultFormatter": "astro-build.astro-vscode"
  }
```
