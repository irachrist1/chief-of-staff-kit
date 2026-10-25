# Chief of staff kit

I spent a day turning my AI agents into a real chief of staff. This is the kit I wish I'd had: give it to your agent and it sets itself up for you.

It works with any agent that can read a web page, from any company. Agents with their own computer, connectors to your email and calendar, memory and background routines get the most out of it. Why I built it and what I learned is in [why.md](why.md).

## How to use it

Send your agent this:

> Read https://github.com/irachrist1/chief-of-staff-kit, starting with START.md, and follow it to set yourself up as my chief of staff.

Your agent will:

1. Read the kit.
2. Interview you in one message: who you are, your goals, your tools, what to hunt for.
3. Write your brief, in your voice, and show it to you for edits.
4. Save it, ask you to connect the tools it needs, and set up its routines.
5. Run a setup check on itself and tell you what works and what doesn't.

Keep your finished brief somewhere private. It's about you, so it never goes back into this repository.

## Before you start (saves you a day)

I learned these the hard way:

- **Check which accounts your agent is really connected to.** My agents' "personal email" connections were often quietly signed in to my school account. Pick one email address for everything the brief does, and make sure every agent can send from it.
- **Say "always allow" for your own address.** Some agents ask permission every time they email you. Allow them to always email your own address, and leave everything else on ask.
- **Put logins where your agent can see them.** If your password manager connects to your agent, it may only see one shared vault. Put the logins it needs there.
- **Give it your documents.** Agents found more from my certificates, tax receipts and statements in Drive than from any portal login. Keep them in one folder and give your agent access to it.
- **Name your meeting notes app.** Most of my action items lived there, and once agents knew that, they found what I'd promised people.
- **Expect "partly" on day one.** Lots of duties only prove themselves once a routine has run or a real meeting happens. Run the setup check again the next morning.
- **Give targets that fit your real week.** My first deep-work target didn't fit around a job and classes, and the agents rightly pushed back.
- **If you use several agents, never assign lanes.** Each one owns everything. If they start dividing up the work in the team room, paste the reset prompt below.

## After setup

**Check what actually works.** Paste the prompt in [setup-check.md](setup-check.md). The agent tests every line of your brief and gives you one table: working, ready (waiting only on a real event), partly, not yet, or can't on this platform. Run it again the morning after setup, and whenever a new model comes out.

**When it drifts, reset it.** Paste this:

> Quick reset. Reread your brief, start to finish. Then tell me in three lines: what you did since we last spoke that I didn't ask for, what in the brief you're not doing yet, and what you'll fix today. Then fix it.

**Score it.** [benchmark.md](benchmark.md) is the list of everything I want an agent to do, written as tests. Every few months, score your agents on it. It's how you see where the technology really is and how fast it's moving.

## What's in here

| File | What it is |
| --- | --- |
| [START.md](START.md) | Setup instructions, written to the agent |
| [brief-template.md](brief-template.md) | The job, which the agent fills in for you |
| [setup-check.md](setup-check.md) | The prompt that makes an agent prove what works |
| [benchmark.md](benchmark.md) | Every test I score agents on |
| [examples.md](examples.md) | The kind of work that counts |
| [why.md](why.md) | Why this exists, and what I learned |

## Using more than one agent

If you use several agents, from the same company or different ones, give each the same kit. The brief has an optional team room: one email thread a day where they share what they're working on and trade ideas. They never split the job. Each one owns all of it, so you never have to remember which agent does what.
