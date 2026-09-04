# You have a robots.txt. You have never read it

*Somebody decided what machines may know about your business. It probably was not you.*

Here is something you can check in about five seconds, on your own website, without buying anything or contacting anyone.

Put your web address into a browser and add `/robots.txt` to the end of it.

Something will load. It is a small plain-text file, usually a dozen lines, and it is one of the oldest conventions on the internet. It tells every automated visitor what it is permitted to read.

## You did not write it

Almost certainly, your website platform generated it for you when the site was built. It has been sitting there ever since, answering on your behalf, and nobody mentioned it because for twenty-five years it did not matter very much. The only things reading it were search engines, and everybody wanted to be in the search engines.

That is the part that has changed.

## The machines reading it are not all doing the same job

Some crawlers collect text to train a model. Some fetch a page at the moment a person asks an assistant a question, so the assistant can answer them accurately. Some are ordinary search indexers doing what they have always done.

Those are genuinely different activities, they run under different names, and they deserve different answers.

**Not wanting your writing and your photographs used as training data is a completely reasonable position.** Plenty of thoughtful people hold it, and there is a directive for it.

**Not appearing in the answer when a potential customer asks an assistant for someone in your trade is a different thing entirely.** Almost nobody chooses that on purpose. It is not a stand on principle. It is being quietly removed from a list you did not know you were on.

A blanket rule does both at once, and it does not tell you which one you just got.

## What to actually look for

Open the file and read it. You are looking for two things.

First, whether there are any lines naming specific crawlers rather than the general `*`. If there are, somebody made a decision about a particular company's robot. Ask yourself whether it was you.

Second, whether anything is disallowed that you would want a customer to find. A `Disallow:` line followed by a path means *do not read this part*. It is worth knowing if that includes your services page.

If you cannot tell — and it is genuinely not obvious, the syntax is forty years old and was designed for engineers — that is not a personal failing. It is a file nobody ever showed you.

## Why I am telling you this rather than selling you something

I build websites. Read the above with the suspicion that deserves.

But this particular thing is free, takes five seconds, and needs no vendor. If your robots.txt says something you did not intend, you now know, and you can have whoever maintains your site change one line.

The reason it is worth your five seconds is not that it is complicated. It is that a decision about who may know your business exists was made for you, by software, on a day nobody told you about — and it is still in force.

If you know someone whose website was built for them and handed over, they have one too. They have not read theirs either.

---

It takes five seconds to read. Almost no owner ever has.

[See what your own robots.txt is actually saying](https://rivercadeconcepts.com/scan?utm_source=github&utm_medium=organic_repo&utm_campaign=rcc_syndication&utm_content=syn_robots_txt_you_never_read__github_public)
