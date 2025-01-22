# Continuous Deployment using AWS Code Pipeline and S3
## THE GAME
A simple memory matching game. The user clicks two cards (images of memes) to match them. If there's a match, the cards disappear from the board. If there's no match, the cards are flipped back to their blank side so the user can try again.

The game consists of HTML, CSS, and JavaScript.

#Ideas for additional features:

• A scoring mechanism
• A timer
• Add additional cards
• Multi-player capabilities so you can compare scores

## The Deployment Environment
The code will be deployed and hosted in S3.

## The Deployment Pipeline
The pipeline is created using the AWS Code Pipeline. It pulls code from GitHub and deploys it to S3 whenever a change is detected in the code.
## Cost
All services used are eligible for the AWS Free Tier. However, charges will eventually accrue, so it's recommended that you shut down resources after completing this tutorial.
