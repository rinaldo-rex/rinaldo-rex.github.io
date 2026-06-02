# Gravitating towards Calendar Versioning {{note: This is not a technical deep-dive on choosing a versioning scheme}}

> ##### Reading time: {{ #reading_time }}.


After almost a decade of being a software develoeper - I've noticed that my personal preference towards _versioning_ in software  gravitates towards Calendric Versioning{{note: Technically specified [CalVer](https://calver.org), semantically meaningful [SemVer](https://semver.org), and on-the-nose [PrideVer](https://pridever.org) 🤣}}. Although there are multitudes of reasonings for that, I'd like to observe a few worth noting for my own posterity. 

### Reason 1: Philosophical

Anybody who's known me throughout my formative years{{note: Higher secondary education through college. Or in other words, throughout my twenties}} would easily point to the fact that I've been exploring too many (schools of) philosophies too early{{note: Based on who you talk to, I suppose}} in life. Maybe that's why I'm naturally leaning towards the only thing that matters for "comparing" {{note: A better word would be _observing_ the change of entropy}} the progress of anything that's describable by human means.

And this reasoning permeats all the other reasoning because as you're probably aware, everything eventually leads back to philosophy{{note: For those who don't know about XKCD: 903 (Read the caption on image hover) and if you wanna visualize this, check [this](https://www.xefer.com/wikipedia) one out!}}


### Reason 2: Need for pause

I'm sure I'll be writing more about my spiritual standpoint in life - both personal and professsional, but for now I'll limit it to the entity - _time_. 

We don't really have _control_ over time{{note: To be frank, I'm not even sure we understand time clearly. The fact that most people can't even comprehend that spacetime is a continuum. That it's not two words as space and time 🤷}}. It proceeds forwards. 

And unfortunately, we've lost track of _perceiving_ time. To be precise - perceiving of _worthy_ time{{note: Kairos vs Chronos}}. Why do we rush everything these days? It makes no sense - given that the more we know, the more we should slow down to process the surplus of the information{{note: at least so far as to filter the noise from the signal}}. Here's how I believe we should slow down. We've somehow narrowed down on this globally recognized and acknowledge Gregorian calendar. And here's where my intuition ripens - We've spent a good number of centuries training ourselves subconsciously to follow and create patterns acknowledging this _cycle_. So why not use it so we simplify and offload the cognitive overload of "progressing" to the existing cycles and patterns?

Modern software engineering has come a long way. (Especially given that I'm writing this in 2026) And agentic engineering has kickstarted a new era of "superfast" development. We've already been plagued with the so-called agile engineering, and being pushed constantly to churn out feature after feature, fix after fix, and versions after versions. It's not sustainable. 
Oftentimes we software engineers are expected to churn too many items in a typical two-week sprint. Why build on a two week cycle in the first place? Especially in this agentic era? So sticking to the calendar sounds the perfect approach to versioning to me. There's much more to life than incrementing multiple numbers per day.

As Mario Zechner (the creator of Pi coding agent) would like to [reiterate](https://youtu.be/RjfbvDXpFls?si=hihTEzFwqN2EFhSy&t=723), Let's slow the fuck down. Let's just stick to the basic years of "cyclic" memory of our biological clocks. Let's keep it simple. We live by the day, month, and year. So let's synchronize our produce{{note: Also produce as in agriculture, which has always been synchronized to seasonal cycles until recent advancements of gene editing!}} to the calendar. 


### Antithesis: Critical software

Here's a reason why any of the above shouldn't matter at all: __*For any critical piece of software or library with frequent changes or where you have to maintain multiple versions and backwards compatibility{{note: Ever heard of the neat [hyrum's law?](https://www.hyrumslaw.com)}}.*__

Semantic version serves better for those situations. It's much more intuitive to understand _breaking_ changes, _compatibility_ concerns, _security_ implications in semantic versions over other versioning schemes.

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
