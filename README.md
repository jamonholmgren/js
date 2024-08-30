# js.jamon.dev

by [Jamon Holmgren](https://jamon.dev)

Check it out here: [js.jamon.dev](https://js.jamon.dev)

<img alt="Screenshot of js.jamon.dev" src="https://github.com/user-attachments/assets/64937fb0-90e6-4cca-8c8e-ad98bee2309d" />


## Why I built this...on my phone...in bed

I was in bed, about to go to sleep, scrolling through Twitter and I saw a code challenge ... something like "change an array of numbers/nulls into smaller arrays split on the nulls". I was intrigued.

I wanted to try it on an actual JS playground and tried a few: codesandbox, replit require auth, the rest suck on mobile (can't select properly and they just suck).

So I thought: I'll make one.

Remember: I'm in bed, on my phone, and my whole reason for wanting this was to not get out of bed.

So I went to the ChatGPT app.

<img src="https://pbs.twimg.com/media/GVCmbLIaIAAWtCm?format=jpg&name=small" />

I long-pressed and copied the HTML code and then opened GitHub in Safari. I created a new repo (this one) and created an index.html and pasted the code in there.

<img src="https://pbs.twimg.com/media/GVCndInb0AEL5WF?format=jpg&name=small" />

I then went to Cloudflare on my phone and created a new Cloudflare Pages instance, and connected it to the Github repo to deploy.

<img src="https://pbs.twimg.com/media/GVCn2P_asAA8e8J?format=jpg&name=small" />

I then added a custom subdomain (js.jamon.dev) and deployed.

And it worked!

<img src="https://pbs.twimg.com/media/GVCpbG8bUAAh3dx?format=jpg&name=small" />

I then proceeded to spend the next hour tweaking it via ChatGPT / copy / paste to Github.

I added:

* Persistence to LocalStorage as you type
* Multiple saved sessions
* Delete session
* Customized title
* Copy as URL for sharing sessions
* Error handling
* Lots of little tweaks

<img src="https://pbs.twimg.com/media/GVCpvhJaEAU7psE?format=jpg&name=small" />

You can try it yourself at [js.jamon.dev](https://js.jamon.dev)!

I never did get to the code challenge. 😂

# License

MIT, enjoy ... but believe me, you could make this yourself in an evening, on your phone.






