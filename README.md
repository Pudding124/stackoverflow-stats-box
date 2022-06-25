<!-- <p align="center">
   <img src="https://i.imgur.com/dIHYraR.png" alt="screenshot" width="500">
  <h3 align="center">📌 Stack Overflow Stats Box </h3>
</p> -->

<p align="center">
   <img src="https://img.shields.io/github/license/Pudding124/stackoverflow-stats-box"/>
</p>
<p align="center">
   Show your stack overflow stats
</p>

> This project is inspired by many projects collected in [awesome-pinned-gists](https://github.com/matchai/awesome-pinned-gists)


## Overview

Show how many Leetcode problems you have solved. 

### Prep work

1. Create a new public GitHub Gist (https://gist.github.com/)
2. Create a token with the `gist` scope and copy it. (https://github.com/settings/tokens/new)

### Project setup

1. Fork this repo
2. Go to the fork repo's **Actions** tab to enable workflow in fork repo
3. Go to the fork repo's **Settings > Secrets**
4. Add the following environment variables:

   - **GT_TOKEN:** The personal access token generated above.
   - **GIST_ID:** The ID portion from your gist url:
     ex: https://gist.github.com/Pudding124/**af7077999686aeac5df7963906bbba93**
   - **USERNAME:** The user name of your stackoverflow id name

5. [Pin your gist](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/pinning-items-to-your-profile)
6. Wait for it to update (the github aciton cron job will run every 6 hours), or you can manually push the repo to trigger the action.
