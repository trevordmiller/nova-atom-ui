_This assumes you have Bash and Git_

- Fork repo
- Branch off `master`
- Run `npm start` to open a development version of Atom
- Inside this Atom development version, select Nova as your theme
- You can open an inspector to inspect the styles of Atom just as you would in a web browser to see what styles to change
- In another instance of an editor, edit `overrides.less`, `styles/ui-variables.less`, or `styles/colors.less` as needed (the other files are left untouched from Atom's default theme setup); the development version of Atom should live-reload with the changes
- Stage, commit, and push
- Submit a pull request
- An admin will merge your pull request and deploy a release
