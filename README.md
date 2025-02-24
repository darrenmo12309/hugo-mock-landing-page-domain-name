# hugo-mock-landing-page
This is a repository for a landing page for a fake product called AquaMetrics. Enjoy.
How the workflow works:
First initializes the action that is needed for the workflow to initiate. In this case it is that changes are committed and pushed to the main branch of the repo
Once this occurs, it defines the OS that the workflow will use to run its commands, which in this case is Ubuntu 22.04
It then checks out my git repo, as well as all submodules and all version history
After this, it sets up hugo and starts to build my site with hugo
Finally, it deploys my built site to github pages.
