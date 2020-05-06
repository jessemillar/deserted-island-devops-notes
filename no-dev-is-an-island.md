# [No Dev is an Island: How to do serverless together](https://desertedisland.club/agenda/#nocnicafee)

Nočnica Fee (Developer Advocate @ New Relic) | @nocnicafee

## Abstract

"Don't chop down trees." "Do leave a hand-written notes."

The very rules of visiting another player's island in Animal Crossing also happen to be great rules for building serverless.

While serverless is easy to build, it's also easy to step on each other's toes, create unexpected dependencies, and alter configuration that breaks other services. This talk gives some guidelines on how to operate harmoniously, store configuration as code, and monitor performance to find problems early.

## Speaker Biography

Nočnica Fee is a serverless developer advocate with New Relic. In her spare time, she enjoys hardware hacking and hand sewing. She's the author of numerous articles and essays on serverless technology and culture, and writes regularly for The New Stack. She dislikes tarantulas no matter what they're worth.

## General Notes

- Nočnica goes by Nica as well
- They work on serverless monitoring
- Serverless isn't a technology, it's "just a concept for who handles what"
- "Serverless is hard for teams, like, actually surprisingly hard"
	- IAM security roles are hard to manage/onboard
	- "Testing is nonexistent"
- "0% of managers like explaining your AWS bill"
	- Try not to surprise your manager with your server bill at the end of the month; give them a heads up
	- You can't 1:1 simulate serverless on your laptop which mandates expenses
- Accept experimentation as part of the dev process
	- Collect metrics to back up experiments/decisions with concrete findings
- Build trust
	- Put experimentation in your budget
	- Use security groups
	- Pick your heroes who hold the keys to production
- Embrace infrastructure as code
	- This helps explain your infrastructure to other people on your team instead of having one subject matter expert who might get hit by a bus
- CI/CD is just as possible with serverless
	- You have to simulate the serverless environment which can be slightly tricky
- Use your users to experiment via canary environments
- Plan ahead for observability

# Documentation

- "Document the why" of your stack
- Embrace the shame in your documentation
	- Be radically honest in your docs
		- Tell the *real* story of why it's build the way it is
			- e.g. "Susan set up this stack and then left and we don't feel smart enough to work on it even though it works great"

# Q&A

- "Any tips for making docs honest and verbose without becoming a wall of text that's daunting to write/read?"
	- @DaveOps#1756
		- "Break a paragraph where there are any commas into bullets and it's like 100% more readable"
		- https://www.sohamkamani.com/blog/how-to-write-good-documentation/
	- @weirdoqueen#2944
		- "I like to write two sets of docs if I can, super in-depth one and quick-ref one; one is for people who REALLY want to know the nitty gritty, other is 'I just want to know how to do x'"
