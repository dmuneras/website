---
title: The Ember Times - Issue No. 69
author: the crowd
tags: Recent Posts, Newsletter, Ember.js Times, Ember Times, 2018
alias : "blog/2018/10/19-the-ember-times-issue-69.html"
responsive: true
---

<SAYING-HELLO-IN-YOUR-FAVORITE-LANGUAGE> Emberistas! 🐹

<SOME-INTRO-HERE-TO-KEEP-THEM-SUBSCRIBERS-READING>

---

## [SECTION TITLE](#section-url)


---

## [SECTION TITLE](#section-url)


---

## [SECTION TITLE](#section-url)


---

## [SECTION TITLE](#section-url)


---

## [SECTION TITLE](#section-url)


---

## [Using Relationships Links or Not? Your Call! 🔗](https://github.com/emberjs/rfcs/pull/387)

Fetching your data from a [JSON:API compliant](https://jsonapi.org/) backend? Not sure how to tell Ember Data **explicitly** to look up an included **relationship** in the payload itself vs. via an additional request using the response's `link` attribute?

Possibly, this will be much easier very soon! [Another new, Ember Data related RFC](https://github.com/emberjs/rfcs/pull/387) proposed the addition of a `shouldFindViaLink` method to the public API of REST **adapters**. According to the proposal, users may overwrite this method - which should return a _Boolean_ to indicate if Ember Data should look up relationship data via links or not - themselves for custom behavior and gain full control of their relational data loading.

You can **read more** about the design of this proposed API [**in the RFC itself**](https://github.com/emberjs/rfcs/pull/387)!


---

## [SECTION TITLE](#section-url)


---

## [SECTION TITLE](#section-url)


---

## [SECTION TITLE](#section-url)


---


## [Contributors' Corner 👏](https://guides.emberjs.com/release/contributing/repositories/)

<p>This week we'd like to thank our siblings for their contributions to Ember and related repositories! 💖</p>

---

## [Got a Question? Ask Readers' Questions! 🤓](https://docs.google.com/forms/d/e/1FAIpQLScqu7Lw_9cIkRtAiXKitgkAo4xX_pV1pdCfMJgIr6Py1V-9Og/viewform)

<div class="blog-row">
  <img class="float-right small transparent padded" alt="Office Hours Tomster Mascot" title="Readers' Questions" src="/images/tomsters/officehours.png" />

  <p>Wondering about something related to Ember, Ember Data, Glimmer, or addons in the Ember ecosystem, but don't know where to ask? Readers’ Questions are just for you!</p>

<p><strong>Submit your own</strong> short and sweet <strong>question</strong> under <a href="https://bit.ly/ask-ember-core" target="rq">bit.ly/ask-ember-core</a>. And don’t worry, there are no silly questions, we appreciate them all - promise! 🤞</p>

</div>

---

## [#embertimes](https://emberjs.com/blog/tags/newsletter.html) 📰

Want to write for the Ember Times? Have a suggestion for next week's issue? Join us at [#support-ember-times](https://discordapp.com/channels/480462759797063690/485450546887786506) on the [Ember Community Discord](https://discordapp.com/invite/zT3asNS) or ping us [@embertimes](https://twitter.com/embertimes) on Twitter.

Keep on top of what's been going on in Emberland this week by subscribing to our [e-mail newsletter](https://the-emberjs-times.ongoodbits.com/)! You can also find our posts on the [Ember blog](https://emberjs.com/blog/tags/newsletter.html).

---


That's another wrap! ✨

Be kind,

the crowd and the Learning Team
