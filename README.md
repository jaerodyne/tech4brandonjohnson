[tech4brandonjohnson.com](tech4brandonjohnson.com)

Sign the Petition In Support of Brandon Johnson, Future Mayor of the City of Chicago. The Chicago Mayoral Runoff Election is on April 4th, 2023. Let’s get to work. – Signed, Jillian Somera, Your Friendly, Neighborhood Election Coordinator for the City of Chicago and Citizen of the 32nd Ward 💙 + Senior Software Engineer who built multimillion dollar fraud detection technology that continues to impact millions of Americans daily + Other Manic Talents

Wanna get involved in the good fight and block his far-right affiliated white supremacist opposition from upholding the same systemic issue shit? Help build some tech while you’re at it. Feel free to contribute to any of these soon to be real open-source repos:
1. Ask Brandon - A Bot that you can ask about Brandon Johnson's political platform + his fav restaurant in Chicago
2. Early Voting d3 Map - An interactive map of Chicago's wards and where you can vote early

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/gomah/bluise)

# Bluise - A Nuxt.js & Netlify CMS boilerplate.

I wanted to explore Netlify CMS & Tailwind CSS, ended up creating this boilerplate.

So far we've got:

- Blog w/ posts, including pagination.
- Configurable manifest & global settings.
- CSS Markdown (Thanks to [https://github.com/iandinwoodie/github-markdown-tailwindcss/blob/master/markdown.css]).
- Dynamic pages.
- PWA ready.
- SEO ready for posts & pages.
- Signup form (using Netlify Forms).
- Tools (Commitlint, Husky).
- Typescript.

Few things I'd like to add in the future:

- Contact form under \_slug.
- Dynamic sections/widgets.
- Responsive CSS markdown.
- Tests

## Quickstart

### Prerequisites

- [Yarn](https://yarnpkg.com/lang/en/docs/install/#mac-tab)
- [Node.js](https://nodejs.org/en/)

```bash
# ensure you have the prerequisites
# install
brew install node && brew install yarn

# OR update
brew update && brew upgrade && brew install yarn

# install dependencies
yarn install

# serve with hot reload at localhost:3000
yarn dev

# build for production with minification
yarn generate

# run all tests
yarn test
```

### Using Netlify CMS

1. Deploy to Netlify.
2. Enable Identity under Settings.
3. Configure registration preferences & external providers if needed.
4. Enable Git Gateway.

_Note: You'll need to specify the Netlify URL when browsing the admin page locally._
