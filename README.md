# ee-configs

## Project devDependencies

`npm i stylelint stylelint-config-prettier stylelint-config-sass-guidelines stylelint-prettier prettier -D`

    "scripts": {
      "prettify": "prettier --write \"assets/**/*.{js,jsx,ts,tsx,css,scss}\" \"!/dist\" \"!node_modules/**\"",
      "stylelint:fix": "stylelint \"assets/**/*.{css,scss}\" \"!/dist\" \"!node_modules/**\" --fix"
    },
