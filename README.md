# PortfolioV2

### A clean personal portfolio. Huge thanks to [harikanani](github.com/harikanani) for template.

# Sections

- Home
- Education
- Projects
- Contact

# How to Use

- Clone this repository (or fork, then clone your fork :) )
- Run `npm i`
- Check it out using `npm start`

# How to Customize

- Replace `homepage` in package.json to your domain name or `https://<username>.github.io`. Delete `/PortfolioV2`.
- In `src/portfolio.js` you can customize your personal portfolio details.
- In `src/theme.js` you can change the theme colors. You can change between Light and Dark theme with the theme switch on the header.
- Use [UnDraw](https://undraw.co/illustrations) to draw SVGs.

# How to Deploy

- Once you are done with your setup and have successfully completed all steps above, you need to put your website online!
- I highly recommend using [Github Pages](https://create-react-app.dev/docs/deployment/#github-pages) to achieve this the EASIEST WAY.
- To deploy your website, you have two options. First you need to create a github repository with the name `<your-github-username>.github.io`. Please don't give it any other name.
- Now, you need to generate a production build and deploy the website.

**Option 1:**

- Run `npm run build` to generate the production build folder.
- Enter the build folder, `git init` and push the generated code to the `master` branch of your new repository. That's it. Done.
  You may need to `git init` and force push at every new build.

**Option 2 ^This deploy^ (will not work with [user pages](https://docs.github.com/en/github/working-with-github-pages/about-github-pages)):**

- Run `npm install gh-pages --save-dev`. This package will help create a distributable version of the React app to a branch named `gh-pages`.
- Run `npm run deploy` to build and create branch `gh-pages`. It will push the `build` files to that branch.
- Then, [configure your GitHub page](https://github.com/gitname/react-gh-pages#8-configure-github-pages).

Now, your website is successfully deployed and you can visit it at `<your-github-username>.github.io`.  


# Technologies used 🛠️

- [React](https://reactjs.org/)
- [graphql](https://graphql.org/)
- [apollo-boost](https://www.apollographql.com/docs/react/get-started/)
- [baseui](https://github.com/uber/baseweb)
- [react-reveal](https://www.react-reveal.com/)
- [styled-components](https://styled-components.com/)

# illustrations 🍥

- [UnDraw](https://undraw.co/illustrations)

# References

Based on https://github.com/harikanani

Illustrations: https://undraw.co/

# Others

Cookie by Google Analytics to track website traffic.
