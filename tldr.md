# Deserted Island DevOps TL;DR

On April 30th, 2020, I ([Jesse Millar](https://jessemillar.com)) attended the [Deserted Island DevOps tech conference](https://desertedisland.club). The conference was advertised as "a free one-day event celebrating DevOps and Animal Crossing." [There were 11 speakers](https://desertedisland.club/agenda/) covering a variety of DevOps-related topics. Over 7,000 people watched the stream on Twitch and there was a large amount of good conversation in the Twitch chat and the Discord server.

This repository contains full notes for every one of the talks. Below are some highlights organized by theme. Since the conference happened in the midst of the COVID-19 pandemic, a large portion of the speakers' remarks revolved around communication and community which I felt was appropriate. In this time of global issue, we're all a little off-kilter. Productivity has taken a dip as we all are struggling to cope with the unique challenges of pandemic life. Taking time to turn inward and let ourselves feel and adapt is necessary. Added care when communicating outward is also important, especially with a lot of the tech industry working from home for the first time. Be concious of your biases and how your words may come across to other people. Be kind. Try to break down barriers between teams. Improve collaboration and everyone benefits. Documentation, blameless postmortems, and avoiding new technology adoption unless necessary are great ideas, especially now.

Since this was the first, in-Animal Crossing conference, Austin Parker, the conference's organizer, wrote [a post](https://aparker.io/posts/deserted-island-devops/) detailing what went into making the conference a reality.

## Themes

### Collaboration/Community

- DevOps and security teams are often at odds, but they don't have to be
	- "Silos are for grain"
- Talk to people outside your org/silo
	- There's always someone willing to share/help and they might have knowledge or experience that you don't
- Good communication takes practice
- Understand that not everyone thinks like you
	- DevOps people:
		- Understand that not everyone wants to quickly slap together software that works quickly but has super open/insecure defaults
		- Loop security in during development
	- Security people:
		- Keep up with the latest trends/technology so you can understand what's being built
		- Try not to be "the Team of No" (learn to talk to people on their level and have conversations instead of just vetoing things)
- You get what you give in a community
- Give to others freely
	- "All gifts must be given without strings attached"
- Conflict is going to happen but it can happen in a way that helps people feel comfortable and heard
- "Psychological safety is a sense of confidence that the team will not embarrass, reject, or punish someone for speaking up." - Amy Edmondson
	- Joking around with people on your team who are friends isn't always perceived by outside parties as being "in jest" and can absolutely prevent people from wanting to share their thoughts or issues
- Model vulnerability to create emotional bonds
- "Teams that do well dealing with impact are those that have a strong common ground."

### Postmortems

- Failure is a chance to collaborate
- Create, discuss, and share blameless postmortems
	- Being "blameless" is almost impossible
		- We, as humans, use blame as a way to "give voice to uncomfortable things"
		- Instead of becoming "blameless" become "blame aware"
- Everyone on a team needs to know that failure is not a bad thing
	- Make this a frequent talking point to drive it home
	- Blameless postmortems really help with this

### Self Care

- You are valuable even when you are not productive
- Breathe
	- If one deep breath is all you can do, great, but many breaths will do wonders
	- Don't turn those breaths into a plethora of sighs
- Be kind to yourself
	- This pandemic situation is not normal
	- This is not just working remotely
	- Lower productivity is normal
	- A global pandemic qualifies as *traumatic*

### Documentation

- "Document the why" of your stack
- Embrace the shame in your documentation
	- e.g. "Susan set up this stack and then left and we don't feel smart enough to work on it even though it works great"
- If you're thinking about writing a doc or tutorial but aren't sure if you want to do it, DO IT

### Adopting New Technology

- "If You Can Wait 6 Months [to adopt a new technology], You Should"
	- If you need something right now, maybe it's worth writing some shims to make it work for you now in the MVP state
- Re-read docs and announcements for products/technologies every six months for things that you're waiting for since things move fast and the product might unexpectedly do exactly what you need after an surprise release

### Miscellaneous

- Mob programming is when you have a bunch of people working together simultaneously on the same work at one computer with a rotation mechanic to allow multiple people to "drive" and get hands-on experience
- "Security isn't a blocker. It's integral."
- "Sometimes getting everything in the right place at the right time working together doesn't happen and you have to be okay with learning and moving on."
- Serverless isn't a technology, it's "just a concept for who handles what"
- Put experimentation in your budget
- Embrace infrastructure as code
- Your car is actually an IoT device
- Don't accept extra requests or allow feature creep in the name of making people like you
- You can harness failure/road blocks to motivate you to push through difficult things (e.g. I can't figure out an error code and that motivates me to slog through the docs for a few hours to learn and understand)
