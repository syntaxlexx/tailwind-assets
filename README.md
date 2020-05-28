# Tailwind-assets
Tailwind css files with different prefixes, grabbable via the CDN

Sometimes you'd like to include tailwind to your workflow, but may end up conflicting with your current stylesheets.
It's always advisable to play safe and use tailwind with all classes prefixed with `tw-` or any other of your choice.

All assets are clean, no extra classes or modifications done on the original tailwind css files.
All files are generated via npm.

## Current Version
All css files are generated based on **tailwind** `v1.4`.

## How to Use
Download either of the versions you prefer to your project. Import the stylesheet in your project and you're done. According to your server configuration (nginx is preferred) the user's browser will download the `.gz` version which is smaller, thereby promoting faster page loads.
So do not forget to copy the `.gz` files!

## Files
### Prefixed with 'tw-'
Files:
- `tailwind.css`
- `tailwind.css.gz`


### Prefixed with 'tw-' and '!important' enforced
It may also benefit you to enforce `!important` tag to `tailwindcss` classes due to existing CSS that has high specificity selectors.
Files:
- `tailwind-important.css`
- `tailwind-important.css.gz`


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
- [Adam Wathan](https://github.com/adamwathan) - Tailwind Creator
- [Lexx YungCarter](https://github.com/lexxyungcarter)

