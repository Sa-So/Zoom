# Zoom
Building an app which integrates within zoom to provide added functionality to the meeting.



# Sample Apps
- https://github.com/zoom/zoomapps-sample-js
- 

# Process I followed
- searched docs - https://developers.zoom.us/docs/
  - broken links on their website!? : https://marketplace.zoom.us/apps?category=zoom-apps
- watched their video tutorials - https://www.youtube.com/playlist?list=PLKpRxBfeD1kGN-0QgQ6XtSwtxI3GQM16R
  - Not helpful: Their tutorials show how to build a legacy app !! - https://developers.zoom.us/docs/build-flow/app-conversion/
- started exploring the basic sample project
  - https://developers.zoom.us/docs/zoom-apps/reference-apps/
  - https://developers.zoom.us/docs/zoom-apps/
- installed wsl for ngrok because for some reason windows is not cool like that
  - https://learn.microsoft.com/en-us/windows/wsl/setup/environment#file-storage
  - PS: installing ngrok is easy if you have chocolatey but installing choco is not ez! - https://chocolatey.org/install 
- had to install node in wsl using nvm - https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04
- Signed up on zoom
- created an app called general app 585!
- Tested out 2 published apps - miro and fathom (fathom did not start)
- Realized zoom is not free for long meetings!
  - buy zoom! - https://zoom.us/opc/buy/config?cartid=awsWANCkx&zcid=2165&utm_source=Product&utm_medium=Product&utm_content=FreeToPro&utm_campaign=UpgradeAnnualClient&_=1711764747796#FullComparisonDialog
  - 


# Questions
## What are shared access permissions?
- https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0063819
## Who is an admin?
- https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0060684#:~:text=Admin%3A%20Can%20add%2C%20remove%2C,Account%20or%20Group%20level%20settings.
  - Role management- https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0064983
## What is zoom rooms?



# Errors I faced
1. https://devforum.zoom.us/t/invalid-redirect-url-4-700-on-valid-redirect-url/15049
2. ngrok not working


# Imp Links
## zoom
- Home page after signing up : https://zoom.us/myhome
- Sample apps - https://developers.zoom.us/docs/zoom-apps/reference-apps/
### Docs
  #### Webhooks
  - https://developers.zoom.us/docs/api/rest/webhook-reference/
  - 
## ngrok
- https://ngrok.com/docs/getting-started/?os=linux#step-4-always-use-the-same-domain - don't copy the installation line for linux from here instead use this : https://ngrok.com/download 
- https://dashboard.ngrok.com/get-started/setup/windows

# Unimportant Links
## zoom
- https://explore.zoom.us/en/terms/ - https://explore.zoom.us/en/terms/?onlycontent=1
- https://explore.zoom.us/en/privacy/ - https://explore.zoom.us/en/privacy/?onlycontent=1
### marketplace
- https://explore.zoom.us/en/marketplace-terms-of-use/
  ### fathom
  - https://fathom.video/terms
  - https://fathom.video/users/sign_up?zoom_app=true - sign in with ms / google only? why? 
### API
- https://explore.zoom.us/en/legal/zoom-api-license-and-tou/
## ngrok
- https://ngrok.com/tos
- https://ngrok.com/privacy
- https://support.microsoft.com/en-us/windows/protect-yourself-from-phishing-0c7ea947-ba98-3bd9-7184-430e1f860a44
