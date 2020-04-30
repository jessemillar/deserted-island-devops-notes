# No Dev is an Island: How to do serverless together

Nočnica Fee (Developer Advocate @ New Relic) | @nocnicafee

## General Notes

- Goes by Nica as well
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

# Documentation

- "Document the why" of your stack
- Embrace the shame in your documentation
- Be radically honest in your docs
	- Tell the *real* story of why it's build the way it is
		- e.g. "Susan set up this stack and then left and we don't feel smart enough to work on it even though it works great"
