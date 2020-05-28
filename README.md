# Tailwind-assets
Tailwind css files with different prefixes, grabbable via the CDN

All assets are clean, no extra classes or modifications done on the original tailwind css files.
All files are generated via npm.

## Current Version
All css files are generated based on **tailwind** `v1.4`.


## Files
### Prefixed with 'tw-'
Sometimes you'd like to include tailwind to your workflow, but may end up conflicting with your current stylesheets.
It's always advisable to play safe and use tailwind with all classes prefixed with `tw-` or any other of your choice.
 

### Prefixed with 'tw-' and '!important' enforced

## Generating your own assets
Here are the steps you can take to generate your own in case you need the experience.
- Setup your own `npm` repo, preferrably a fresh one
- Update your `package.json` accordingly as in this repo's `package.json`
- Add the `tailwind.config.js` as in this repo's `tailwind.config.js`
- Run `npm install` followed by `npm run production` or whichever `npm` command compiles the code to production. (Mine is based off Laravel's)
- Copy the generated tailwind css files to your project

## Requests and Updates
Should you wish to request for more prefixed tailwindcss files or updates, feel free to contact
- [Lexx YungCarter](mailto:lexxyungcarter@gmail.com)
- [AceLords](info@acelords.space)

# Credits
- Adam Wathan - Tailwind Creator

