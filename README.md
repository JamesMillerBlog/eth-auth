# Eth-Auth
This repository is a template from the Wrapper.js library.

## How to commit to this repo
You can either create a branch and raise a PR as you would any other repository, or you can make changes directly in the Wrapper.js Repository.

This is possible, as this repository is a subtree of Wrapper.js, subtree commands to remember are:
- The command to add a subtree to a repository (necessary on initial creation only): ```git subtree add --prefix templates/eth-auth https://github.com/JamesMillerBlog/eth-auth.git main --squash```
- The command to add a remote to the repository: ```git remote add -f eth-auth https://github.com/JamesMillerBlog/eth-auth.git```
- The command to fetch webxr main branch: ```git fetch eth-auth main```
- The command to pull webxr main branch: ```git subtree pull --prefix templates/eth-auth eth-auth main --squash```
- The command to push to webxr main branch: ```git subtree push --prefix templates/eth-auth eth-auth main```
