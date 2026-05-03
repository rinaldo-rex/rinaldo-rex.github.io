# Gravitating towards Calendar Versioning {{footnote: This is not a technical deep-dive on choosing a versioning scheme}}

> ##### Reading time: {{ #reading_time }}.


After almost a decade of being a software develoeper - I've noticed that my personal preference towards _versioning_ in software  gravitates towards Calendric Versioning{{footnote: Technically specified [CalVer](https://calver.org), semantically meaningful [SemVer](https://semver.org), and on-the-nose [PrideVer](https://pridever.org) 🤣}}. Although there are multitudes of reasonings for that, I'd like to observe a few worth noting for my own posterity. 

### Reason 1: Philosophical

Anybody who's known me throughout my formative years{{footnote: Higher secondary education through college. Or in other words, throughout my twenties}} would easily point to the fact that I've been exploring too many (schools of) philosophies too early{{footnote: Based on who you talk to, I suppose}} in life. Maybe that's why I'm naturally leaning towards the only thing that matters for "comparing" {{footnote: A better word would be _observing_ the change of entropy}} the progress of anything that's describable by human means.

And this reasoning permeats all the other reasoning because as you're probably aware, everything eventually leads back to philosophy{{footnote: For those who don't know about XKCD: 903 (Read the caption on image hover) and if you wanna visualize this, check [this](https://www.xefer.com/wikipedia) one out!}}


### Reason 2: Need for pause

I'm sure I'll be writing more about my spiritual standpoint in life - both personal and professsional, but for now I'll limit it to the entity - _time_. 


### Reason 3: Makes sense for a blog

I could of course simply add the date of the blog post{{footnote: Or since this is hosted on Github, you can literally just check my commit history}}. But somehow it didn't feel intuitive to me. Primarily because I randomly stop blogging altogether. And it's in an eternal stagnation. People coming to my blog has to search for the date to understand that this older version of me is dumber than the current version of me. 

Basically provides an instant context of time. You see a post of mine under \\(26.5.1.2._{26.5.3}\\)? - You can instantly deduce the seed for that post was 2026 May 1st. And the superscript is basically when it was last revisited/revised (2026, May 3rd). That's all you gotta know about a blog. If you're reading this blog in the future and it hasn't been updated or revisited by me to update my growth in how my perspective has shifted (or hardened), you can safely ignore any strong notions I had about it. 

| ![](blog_calver.png) | 
|:--:| 
| *An example of how I use CalVer on this blog* |

### Anti-Reason: Critical software

Now that I've laid out why calendar versioning is relatively more attractive to me over other versioning - here's a reason why any of the above shouldn't matter at all: __*For any critical piece of software or library with frequent changes.*__

Semantic version serves better for those situations. It's much more intuitive to understand _breaking_ changes, _compatibility_ concerns, _security_ implications in semantic versions over other versioning schemes.

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
