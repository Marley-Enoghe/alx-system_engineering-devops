this  login service stopped working. About 20% of our users couldn't log in. Why It Happened: There was a mistake in how we set up the login system.

What We Did wrong: Found the Issue: Our monitoring system noticed lots of login failures.

Investigation: Look at the logs to figure out what went wrong.

Initial Guess: Guessed it might be a hacker or a problem with the software update.

Got Help: Asked our security team to check things out.

Mistakes We Made:

Thought it was a software update problem at first. Checked the database even though it wasn't the issue. Asked for Help:

Brought in the DevOps and Security teams to help. Fixed the Issue:

Discovered it was a setup mistake. Went back to the way things were before the mistake. Added extra security to prevent it from happening again. What We Learned: Why it Broke: There was a mix-up when we changed something in the login system.

How We Fixed It: We went back to how it was before the change, and we added extra security.

How We'll Avoid This Next Time: Things to Make Better:

Test changes better before making them live. Keep a closer eye on unusual login patterns. To-Do List:

Check changes more carefully before putting them live. Improve the tools that watch for weird login patterns. Be more careful with how we set up things in the future. wrote a postmortem review in this directory
