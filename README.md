# Table of Contents

- [About the project](#About-the-project)
- [Live Demo](#Live-Demo)
- [Screenshots](#Screenshots)
- [Functionality](#Functionality)
- [Technologies](#Technologies)
  - [Front-end](#Front-end)
- [How to run](#How-to-run)
- [How to test](#How-to-run-tests)

# About the project

The project is a website built in React that allows a user to choose a city in india to view air quality in cigarettes and particulate matter. The site allows language translation in english and hindi. The project follows a cicd workflow that deploys the optimized build to amazon s3 via github actions.

# Live Demo

<a title="Deployed on aws" href="http://bbc-news-test.s3-website-us-east-1.amazonaws.com/">http://bbc-news-test.s3-website-us-east-1.amazonaws.com/
</a>

# Screenshots

<details><summary>English Version Hero Section</summary>
<p>
<img src="./.readme/english_home.png" >
</p>
</details>
<details><summary>Indian Version Hero Section</summary>
<p>
<img src="./.readme/indian_home.png" >
</p>
</details>
<details><summary>English Version Dropdown Section</summary>
<p>
<img src="./.readme/english_dropdown.png" >
</p>
</details>
<details><summary>Indian Version Dropdown Section</summary>
<p>
<img src="./.readme/indian_dropdown.png" >
</p>
</details>

# Functionality

- [x] Ability to switch languanges between english and hindi
- [x] Ability for users to choose a city and see air quality in the form of cigarettes and particulate matter

# Technologies

- [React](https://create-react-app.dev/)
- [Bootstrap](https://getbootstrap.com/)
- [Webpack](https://webpack.js.org/)
- [Github actions](https://lab.github.com/MSUSDEV/build-end-to-end-cicd-capabilities-directly-in-github)
- [AWS-S3](https://aws.amazon.com/s3/)

# How to run

```bash
# Clone the repo
$ git clone https://github.com/josphinenzila/air_quality_bbc_test.git
# cd to the project directory
$ cd air_quality_bbc_test
# Install dependancies
$ npm i

# npm run to start the server
$ npm start

```

# How to run tests

Configure .env file at the root of the project, use the following data:

```
SKIP_PREFLIGHT_CHECK=true
```

Use the command below to run tests:

```
$ npm run test
```

# Generate optimized build

```
$ npm run build

```
