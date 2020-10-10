# git-tagging-using-gitlab-ci
The code given in this section lets you tag your branch from pipeline itself. 
Tagging is properly explained in this link: https://medium.com/@neronjoseph.sep/tag-your-git-repo-using-gitlabs-ci-cd-pipeline-a7963c2274d2

Here there 2 methods of tagging: 
1. Using Gitlab credentials
2. Using Gitlab personal access token

Choose the code and you can add that in your .gitlab-ci.yml file to run in gitlab pipeline. 

Note: In order to use Gitlab's personal access token, we need to create the token first. Use this link to create token. Link: https://docs.gitlab.com/ee/user/profile/personal_access_tokens.html
