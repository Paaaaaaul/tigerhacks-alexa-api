# tigerhacks-alexa-api 
A custom skill for Amazon's Alexa usable with Amazon Echo and Amazon Dot. 
We created this project during TigerHacks 2017 at the University of Missouri - Columbia. 
Our intention is to help journalist to be able to take notes without writing. Alexa can store all notes they may need to take onto our Firebase server. We render all notes from the server in real-time to a website (currently only in localhost) where notes can be reviewed and deleted. 

The repo for the website can be found here: https://github.com/bpallares/Tigerhacks2017

Credits to Boris Pallares, Alex Andrei, Zhuocheng Shang and Marouen Helali.

# Functionality
If you want to test this skill clone this repo to your computer.

`git clone https://github.com/Paaaaaaul/tigerhacks-alexa-api.git`

You will need to sign up for AWS Lambda from Amazon and use their Developer.Amazon Portal. 
Go through the tutorials to gain so more insights how to set up a new skill. Then upload the code into your AWS Lambda.

We developed following intents (abilities):
- *open Skill* - in our case we called our skill 'Dictate', simply say 'Alexa, open Dictate' and the skill is launched.
- *create new project* - simply say create a new project and name your project to start a new project.
- *add notes* - say 'add a new note' and add the note you want to add.
- *help* - if you unsure how to use our functions ask Alexa for help!


# Contribution
If you want to help me and my team continue developing this skill further so that future journalists can work paperless and enjoy an comforting virtual companion like Alexa to help them kick of their articles feel free to push changes since there is still a lot to do. Everything starts with an idea.
