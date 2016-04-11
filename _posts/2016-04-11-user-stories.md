---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: "Here are a few comments that emerged from notes I took at Amir Barylko’s recent presentation, User Stories Deep Dive.\_\n"
datePublished: '2016-04-11T05:42:24.757Z'
dateModified: '2016-04-11T05:41:14.423Z'
title: "User Stories\_"
author: []
sourcePath: _posts/2016-04-11-user-stories.md
published: true
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
url: user-stories/index.html
_type: Article

---
Here are a few comments that emerged from notes I took at Amir Barylko's recent presentation, _[User Stories Deep Dive][0]_. 
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/3e1fbd6c-f060-49a5-a7db-f7c6ab745d55.jpg)

# User Stories 

The work that comes out of user stories has a much greater chance of failing to achieve its goals when stories have poor quality. 

User stories are intended to be placeholders for future conversations. User story quality suffers if we forget or ignore this goal when we set out to record them. The same is true when we set out to actually use the stories to do some work. 

It's really about the quality of the conversation, not the quality of the user story itself. But it all starts with the user story. 

When problems in the work are caused by the user story, it's hard to know what went wrong. By the time the work has failed, **there's so much distance between the story and the outcome that it's impossible to know what exactly went wrong**. 

So, it can be tricky for teams to measure the quality of their user stories. I don't know that it's even reasonable to measure user story quality. It's worthwhile to at least take stock of the quality of the conversations that come out of stories as you go, say, in a retrospective. **Improving user stories is likely to have a butterfly effect on how well the work goes**. 

## Guidelines to creating high-quality user stories 

One common way to improve stories is to use the mnemonic, [INVEST][1].

While handy for remembering each of the qualities of a great user story, INVEST also illustrates the real value that stories are meant to create in the first place.

There's a bit of debate about the format of user stories. In general, the format is not actually important. You can really write user stories however you like --- as long as the stories hit the INVEST qualities, do whatever your team feels is best.

# Scenarios

Scenarios are intended to give just a bit of detail about how the user story should actually work. They clarify the intended outcome of the stories in a way that fosters shared understanding among business people, developers and even users.

So, if the user story says something about the fact that users need to be able to purchase your products, the scenario might say something about how, when someone visits the product page and clicks "purchase," then they should be able to enter some payment details.

In addition to giving developers a near ready-made test case to transcribe into their test suite, **scenarios are also very useful for testing the quality of your user story**.

For example, if there are too many scenarios for a single user story, or if it takes too long to work out how to write the scenarios, then the story is too complex and needs to be split up. If you're not even sure where to start, or how to write a scenario for a user story, then perhaps the user story is not clear enough. 

I mostly write PHP these days, so I'm a big fan of [Behat][2] and [Mink][3].
Beat uses a scenario syntax called [Gherkin][4].
If you use Laravel, there's a pretty sweet [Behat Laravel extension][5]. It works well.

[0]: http://www.meetup.com/agilewpg/events/223767341/
[1]: http://xp123.com/articles/invest-in-good-stories-and-smart-tasks/
[2]: http://docs.behat.org/en/v3.0/
[3]: http://mink.behat.org/en/latest/
[4]: http://docs.behat.org/en/v3.0/guides/1.gherkin.html#gherkin-syntax
[5]: https://github.com/laracasts/Behat-Laravel-Extension