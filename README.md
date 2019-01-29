# Test Projection i18n

Nothing. Just to test if i18n works inside `<ng-content>`, since it was claimed
to be this super static content projection that I banic-ed and tried it out.

### How

1. Run `yarn build:fr`
2. Open `dist/fr` folder
3. Serve it with something something (idk just use `python -m http.server`)
4. Verify that the bottom two text are in French instead of English
