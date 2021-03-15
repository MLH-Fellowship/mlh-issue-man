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
uses: sammychinedu2ky/issue-man@v1
with:
  myToken: '${{ secrets.GITHUB_TOKEN }}'
  key: '${{secrets.KEY}}'
  endpoint: '${{secrets.ENDPOINT}}'
```
