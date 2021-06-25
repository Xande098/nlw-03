<h1 align="center">
    Project: Happy
    <h1 align="center">
    <img alt="nlw-03" title="NLW #03" src=".github/nlw-03.jpg" width="260px" />
    </h1>
    <h3 align="center">Application to facilitate the connection of people with children living in foster homes.</h3>
</h1>

<p align="center">
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=7159c1&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=7159c1&labelColor=000000" />
</p>

<br>

## 🚀 Technologies

This project was developed with the following technologies:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [TypeScript](https://www.typescriptlang.org/)
- [Expo](https://expo.io/)

## 💻 Project

Happy is a project that helps to connect people with childcare homes, being able to consult the times available for visits and the rules so that they can visit them and bring joy to children.

<div style="display: flex">
  <div align="center">
    <strong style="font-size: 18px">Web</strong>
    <h1 align="center" style="margin-right: 28px">
      <img alt="web-version" title="Home-web" src=".github/home-web.svg" width="620px" />
    </h1>
  </div>

  <div align="center">
    <strong style="font-size: 18px">Mobile</strong>
    <h1 align="center">
      <img alt="mobile-version" title="Home-mobile" src=".github/home-mobile.svg" width="180px" />
    </h1>
  </div>
</div>

## 🔖 Layout

You can view or layout the project in the format through [this link](https://www.figma.com/file/wqJ1jlXGLSloaIsh8J4Mmr/My-Happy-Web?node-id=0%3A1). Remembering that you will need to have a [Figma](http://figma.com/) account.

## :information_source: How to use

To clone and run this application, you'll need [Git](https://git-scm.com) + [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable) installed on your computer.

From your command line:

### Install API
```bash
# Clone this repository
$ git clone https://github.com/Xande098/nlw-03.git

# Go into the repository
$ cd nlw-03/backend

# Install dependencies
$ yarn

# Run Migrates
$ yarn typeorm migration:run

# Start server
$ yarn dev

# running on port 3333
```

### Install Front-end

```bash
# Clone this repository
$ git clone https://github.com/Xande098/nlw-03.git

# Go into the repository
$ cd nlw-03/web

# Install dependencies
$ yarn

# Run
$ yarn start

# running on port 3000
```

### Install Mobile

```bash
# Clone this repository
$ git clone https://github.com/Xande098/nlw-03.git

# Go into the repository
$ cd nlw-03/mobile

# Install dependencies
$ yarn

# Run
$ yarn start

# Expo will open, just scan the qrcode on terminal or expo page

# If some problem with fonts, execute:
$ expo install @expo-google-fonts/nunito expo-font

```

## 🤔 How to contribute

-  Make a fork;
-  Create a branch with your feature: `git checkout -b my-feature`;
-  Commit changes: `git commit -m 'feat: My new feature'`;
-  Make a push to your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## :memo: License

This project is under the MIT license. See the [LICENSE](LICENSE.md) for details.

---

Made with ♥ by Alexandre Sobota :wave: [Get in touch!](https://www.linkedin.com/in/alexandre-sobota)