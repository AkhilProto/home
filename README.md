# [Developer's Portfolio](https://hashirshoaeb.github.io/home)

[![Site preview](/public/social-image.png)](https://hashirshoaeb.github.io/home)

It is a personal static website/portfolio template hosted with GitHub Pages, built to showcase my recent projects. Site URL / Demo: [hashirshoaeb.github.io/home](https://hashirshoaeb.github.io/home).

## Table of Contents

- [Technology Stack 🛠️](#technology-stack-)
- [Structure](#structure)
- [Sharing](#sharing)
- [Setup And Deployment 🔧](#setup-and-deployment-)
- [Contributing](#contributing)
- [Issues](#issues)
- [Upcoming features](#Upcoming-features)
- [Showcase 🚀](#showcase-)
- [Contributors ✨](#contributors-)
- [License 📄](#license-)

## Technology Stack 🛠️

Dependencies defined in package.json:

- [Reactjs](https://reactjs.org/)
- [Bootstrap](https://getbootstrap.com/)
- [Typist](https://github.com/jstejada/react-typist)
- [GitHub API](https://developer.github.com/v3/repos/)
- [Instagram API](https://www.instagram.com/developer/embedding/)

## Structure

- Body
  - Name | Profession
  - Contact / Follow / Find me / Facebook / LinkedIn / GitHub / Instagram / Email / CodePen
  - Resume
- About Me
  - Display picture (using Instagram API)
  - Interests, Goals and Hobbies
  - Things I'm good at (Skills)
- Projects (using GitHub API)
- Footer
  - Acknowledgements (contributors)
  - Copyrights - open source
  - (quote: Dream big, Think big)

## Sharing

Project is open source. Feel free to make your own version. All you need to do is to fork the project and edit the [src/configurations.json](./src/configurations.json) file. Mark star ⭐ if you like the project.

## Prerequisites

You should have [Node.js](https://nodejs.org/en/) and [Git](https://git-scm.com/) installed on your PC. You should also own a GitHub account.

## Setup And Deployment 🔧

1. To Get Started, Fork the repository to your GitHub account:
2. Clone the forked repo from your account using:

   ```bash
     git clone https://github.com/<your-username>/home.git
   ```

3. Open in editor and edit [src/configurations.json](./src/configurations.json) file.

4. Change URL in [package.json](./package.json) file:

   ```json
   "homepage": "https://<your-username>.github.io/home"
   ```

5. Edit [title](./public/index.html#L32) and meta [description](./public/index.html#L13) in [public/index.html](./public/index.html).

6. After editing run the following bash commands:

   ```bash
   npm install
   npm start
   ```

7. To deploy website run:

   ```bash
    npm run deploy
   ```

8. Congrats your site is up and running. To see it live, visit:

   ```https
     https://<your-username>.github.io/home
   ```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Issues

If anyone is looking to make some contribution, the following are issues that you can solve:

- [ ] UI improvements
- [x] Grammar check | Spelling mistakes
- [ ] Code optimization
- [x] Hover property on social icons
- [ ] Routing

## Upcoming features:

- [ ] Button and place for resume/CV.
- [ ] Option: add or not to add Instagram's display picture.
- [ ] Number of projects to show in website.

## Showcase 🚀

Have you changed something in the code to create your own version? Feel free to share with me, I will list them in this space.

Following awesome people have created their own version.

1. [@khizarkhizar](https://github.com/khizarkhizar) version: https://khizarkhizar.github.io/home/

2. [@meullah](https://github.com/meullah) version: https://meullah.github.io/home/

3. [@AymunTariq](https://github.com/AymunTariq) version: https://github.com/AymunTariq/home/

## Contributors ✨

<table>
  <tr>
    <td align="center">
      <a href="https://www.facebook.com/hashir.shoaeb">
        <img src="https://avatars2.githubusercontent.com/u/35165481?v=4" width="100px" alt="" />
        <br />
        <sub><b>Hashir Shoaib</b></sub>
      </a>
      <br />
    </td>
    <td align="center">
      <a href="https://github.com/iprithvitharun">
        <img src="https://avatars2.githubusercontent.com/u/58725708?v=4" width="100px" alt="" />
        <br />
        <sub><b>Prithvi Tharun</b></sub>
      </a>
      <br />
    </td>
    <td align="center">
      <a href="https://github.com/CodyJasonBennett">
        <img src="https://avatars3.githubusercontent.com/u/23324155?s=460&v=4" width="100px" alt="" />
        <br />
        <sub><b>Cody Bennett</b></sub>
      </a>
      <br />
    </td>
  </tr>
</table>

## License 📄

[LGPL-3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html)
