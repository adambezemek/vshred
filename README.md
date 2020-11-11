# VShred Code Test

## Prerequisites
- [node](https://nodejs.org/en/) - at least v10.13 We recommend you have the latest LTS version installed.
- [yarn](https://classic.yarnpkg.com/en/) - not required but preferred

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Approach
1. Use Nuxt.js to show off Vue.js skills and the ability to build a preformat static gen site.
2. Use TailwindCSS to highlight it's quick prototyping capabilities and configurability.
3. Deploy to Netlify to show CD/CI process knowledge.
4. See Lighthouse scores attached to email, all categories are in the 90's! 🥳

## Deviations from the Design
The deviations I made from the design were purely due to time constraints. The features are completely buildable, just tedious. Rather than working into tomorrow, I figured I would get you something this evening to review.
- *On mobile:* Affixing the button to the bottom of the screen on scroll.
- *On Desktop:* Showing the additional images in the carousel to the left. The slider I used has configurations to do this, it just requires pretty detailed CSS to finish the feature.
- *Lastly:* I used the Google Font [Montserrat](https://fonts.google.com/specimen/Montserrat) instead of Proxima Nova, because it needs to be bought via Adobe. 