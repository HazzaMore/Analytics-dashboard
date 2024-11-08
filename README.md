# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Installs to create from scratch
* start with this: https://tailwindcss.com/docs/guides/vite 
* Install `npm i react-router-dom lucide-react recharts`
* Animations install `npm i framer-motion`

## Other setup notes
* If you are getting errors with using test containing `'` such as `it's` then add `"react/no-unescaped-entities": "off",` to the '/eslint.config.js' rules.
* For issues with prop-types where they are 'missing in props validation' then add `"react/prop-types": "off",` to the same place as above.
* If changing the case sensitivity of folders, run `git config core.ignorecase false` to allow the changes to be tracked in VSC

## Extra To do:
* Make the animation delay for components passed through as a prop (so if the component is reused, or replaced it won't mess things up)
* Link the data into a database
* Work out how to add an average trend line to some of the graphs
