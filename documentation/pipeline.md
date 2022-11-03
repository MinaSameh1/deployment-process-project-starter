## PIPELINE

#### Steps:

1. Push Code to github master branch.
1. CircleCI Then grabs the code.
1. Installs front and backend deps.
1. Lints the frontend.
1. Builds the front and backend.
1. Waits for approval
1. If approved by a dev
1. Installs aws, eb and sets env vars.
1. Deploys both apps.
