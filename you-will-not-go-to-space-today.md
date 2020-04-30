# [You Will Not Go To Space Today](https://desertedisland.club/agenda/#jacquiegrindrod)

Jacquie Grindrod (Developer Advocate @ HashiCorp) | @devopsjacquie

## Abstract

When your application is mission critical, DevOps can feel a lot like fixing a spaceship to go to space. It can be hard to get all the right pieces in the right places at the right time, & sometimes all you can do is take a step back and have a little fun with what you've learned. That's how a software engineer & a devops practitioner who have neither been to space nor built a video game before found themselves swapping roles as well as building a game about making it to space to bring people together during a time of unprecedented virtualization.

We'll share our progress & mistakes made as well as some of the highs & lows of our game development foray (featuring challenging moments such as "why is it green in my terminal and pink in yours??" & "what are tilesets and why are they so hard?!")

Topics you can expect to hear in this talk:

- XKCD's "You Will Not Go to Space Today" as a metaphor for devops
- Prototyping jump start vs learn-as-you-go development
- Raft in a Game for dynamic room generation and scaling
- DevOps concepts applied to (amateur) game design
- Some things we used: Godotengine & GDScript, Go & termbox, Jenkins-X, AWS, Nomad, Consul, Vault, Terraform

## Speaker Biography

Jacquie Grindrod is a developer advocate for HashiCorp where she's able to apply her passion for solving problems with a holistic approach by bridging the gaps between teams and systems. From making making healthcare accessible to creating a winning networking application for women in tech at ElleHacks 2018, Jacquie works to collaborate and empower communities around her. In 2019, Jacquie was recognized as Canada's Top 30 Under 30 Developers and spoke at DevOpsDays Toronto. A notable ACNH moment for her was shouting 'Yay I finally paid off my house loan!' to which her partner promptly responded 'why do you even play this game??'

## General Notes

- They built a game that's meant to improve person-to-person communication during the pandemic
	- Inspired by the Spaceteam mobile game
- They livestreamed a large portion of the game's development which is educational and noble
	- The stream is honest and potentially helps people find motivation to fight through initial learning curves (we need more games in the world!)
- See recording for technical architecture details
	- There's a good initial model for scalable multiplayer architecture involving Nomad/Consul in AWS
- "Sometimes getting everything in the right place at the right time working together doesn't happen and you have to be okay with learning and moving on."
- It's tricky getting users to play your game since, often, the onboarding process of playing a new game involves so many steps that potential players lose motivation (e.g. Have to create a Steam account, download/install Steam, install the game, figure out the game, etc.)
- They asked for feedback from multiple beta testing users

## Lessons Learned

- Be willing to pivot if your initial plan isn't working out
- Tradeoffs have to happen to push progress (e.g. pretty or functional?)
- Be gentle with yourself
	- Don't put so much stress on yourself when you're learning that it kills the enjoyment
- DevOps culture can be applied to unexpected schools of thought
	- Keep an open mind when trying new things
- Empathetic documentation is key
	- If you're thinking about writing a doc or tutorial but aren't sure if you want to do it, DO IT
	- "We need you"

## Q&A

- What was your strategy for testing the game since so much of the level was randomly generated? e.g. How did you make sure that things that were supposed to be in the level actually spawned in?
	- "Try and try and try again"
	- Run it on different machines manually
	- Run through the levels by hand
