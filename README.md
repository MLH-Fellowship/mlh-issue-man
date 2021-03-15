![mlh-issue-man](https://socialify.git.ci/MLH-Fellowship/mlh-issue-man/image?description=1&descriptionEditable=A%20GitHub%20Action%20AI%20Bot%20for%20managing%20comments%20in%20the%20GitHub%20Issues&font=Source%20Code%20Pro&language=1&pattern=Brick%20Wall&theme=Dark)


# MLH Issue Man

Toxicity in online spaces poses a serious challenge for platforms and publishers. Online abuse and harassment silence important voices in conversation, forcing already marginalized people offline. **MLH Issue Man** is a GitHub Action AI Bot for managing comments in the GitHub Issues of a repository by giving warning to users that post adult content(image).

![MIT License](https://img.shields.io/github/license/MLH-Fellowship/mlh-issue-man) ![Issues](https://img.shields.io/github/issues-raw/MLH-Fellowship/mlh-issue-man) ![Code Quality](https://img.shields.io/badge/code%20quality-A-brightgreen) ![PRs](https://img.shields.io/github/issues-pr/MLH-Fellowship/mlh-issue-man) ![Forks](https://img.shields.io/github/forks/MLH-Fellowship/mlh-issue-man?style=social) ![Stars](https://img.shields.io/github/stars/MLH-Fellowship/mlh-issue-man?style=social) 

## Features
- Helps to maintain the code of conduct
- Helps in making the community more inclusive and welcoming
- Helps to prevent offensive, derogatory or toxic ambience on GitHub
- Moderators can use it to quickly prioritize and review comments that have been reported.
- Gives feedback to commenters who post toxic comments
- Enables healthy conversations

## Demo Video
<a href="https://www.youtube.com/watch?v=hltpHN_bz1o" target="_blank" rel="noopener">
  <img src="https://user-images.githubusercontent.com/42115530/111118991-8863ee00-858f-11eb-92da-b9b5540484dc.png" alt="MLH Issue Man"
	title="MLH Issue Man" width="500px" />
</a>

## Browser Support
- **Firefox**:	version 4 and up
- **Chrome**:	any version
- **Safari**:	version 5.2 and up
- **Internet Explorer/Edge**:	version 8 and up
- **Opera**:	version 9 and up
> **Note**: Support for modern mobile browsers is experimental.

## Technology Stack used:

<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img src="https://img.shields.io/badge/markdown-%23000000.svg?&style=for-the-badge&logo=markdown&logoColor=white"/> <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/> 

- **Frontend**: GitHub Actions
- **IDE**: VS Code
- **Design**: Adobe Photoshop, Canva
- **API Testing & Documentation**: Postman
- **Version Control**: Git and GitHub
- **Code Hosting**: GitHub 

### How to Get Started?

- Fork and Clone the repo using
```
$ git clone https://github.com/MLH-Fellowship/mlh-issue-man.git
$ cd mlh-issue-man
```
- Install node dependencies
```
$ npm install
```
- Run Server at localhost using
```
$ npm start
```

### How it works?

This action warns a user when an adult content(image) is posted by the user as a comment under GitHub issues

#### Inputs
 `myToken`

**Required** Your GitHub Token.

#### `key`

**Required** The Key of your Azure Computer Vision Resource.

#### `endpoint`

**Required** The endpoint of your Azure Computer Vision Resource.


#### Example usage
```
uses: mlh-fellowship/mlh-issue-man@v1
with:
  myToken: '${{ secrets.GITHUB_TOKEN }}'
  key: '${{secrets.KEY}}'
  endpoint: '${{secrets.ENDPOINT}}'
```

## Team:

> "Alone we can do so little; together we can do so much."

| S.No. | Name | Role | GitHub Username:octocat: |
| --------------- | --------------- | --------------- | --------------- |
| 1. | Pragati Verma | Developer | [@PragatiVerma18](https://github.com/PragatiVerma18) |
| 2. | Samson Amaugo | Developer| [@sammychinedu2ky](https://github.com/sammychinedu2ky)  |
| 3. | Raphael Noriode | Developer | [@Oghenebrume50](https://github.com/Oghenebrume50)  |

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody><tr>
    <td align="center"><a href="https://www.linkedin.com/in/PragatiVerma18/"><img alt="" src="https://avatars2.githubusercontent.com/u/42115530?v=4" width="100px;"><br><sub><b>Pragati Verma</b></sub></a><br><a href="https://github.com/MLH-Fellowship/mlh-issue-man/commits?author=PragatiVerma18" title="Code">💻</a></td>
	      <td align="center"><a href="http://swacblooms.com/"><img alt="" src="https://avatars.githubusercontent.com/u/36219292?s=400&u=868da142ccf632024316f4392db9478211bf2d69&v=4" width="100px;"><br><sub><b>Samson Amaugo</b></sub></a><br><a href="https://github.com/MLH-Fellowship/mlh-issue-man/commits?author=sammychinedu2ky" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Oghenebrume50"><img alt="" src="https://avatars.githubusercontent.com/u/37092867?s=400&u=e66e097ef9f529e5937662e91d65f866bf2558bf&v=4" width="100px;"><br><sub><b>
Raphael Noriode</b></sub></a><br><a href="#Oghenebrume50" title="Code">💻</a></td>
  </tr>
</tbody></table>


<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!


[![Uses Git](https://forthebadge.com/images/badges/uses-git.svg)](https://github.com/MLH-Fellowship/mlh-issue-man) [![Uses JS](https://forthebadge.com/images/badges/uses-js.svg)](https://github.com/MLH-Fellowship/mlh-issue-man)
[![Built with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/MLH-Fellowship/mlh-issue-man) [![Built By Developers](https://forthebadge.com/images/badges/built-by-developers.svg)](https://github.com/MLH-Fellowship/mlh-issue-man) 
