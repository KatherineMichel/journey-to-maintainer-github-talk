# Journey to Maintainer- GitHub

## Table of Contents

- [About](#about)
- [Slides and Script Table of Contents](#slides-and-script-table-of-contents)
- [Slides and Script](#slides-and-script)   
- [Attribution](#attribution)
- [Contact Kati](#contact-kati)
- [Copyright](#copyright)

<hr>

## About

Slides and script for a talk Katherine "Kati" Michel ([Twitter](https://twitter.com/KatiMichel), [GitHub](https://github.com/KatherineMichel)) gave, published Friday, June 11, 2021.
 
Slide Deck
* [Original slide deck](https://docs.google.com/presentation/d/1h4B_3kWntZBQfK6zE_PuZ-lrxI-whuyWAMyFfprYDo4/edit?usp=sharing)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Slides and Script Table of Contents

- [Journey to Maintainer](#journey-to-maintainer)
- [Affiliations](#affiliations)
- [Talk Goals](#talk-goals)
- [Milestone: Django Was Born, 2003](#milestone-django-was-born-2003)
- [Django is Invented at LJW](#django-is-invented-at-ljw)
- [If Only I Had Known](#if-only-i-had-known)
- [If Only I Had Known](#if-only-i-had-known)
- [Milestone: Becoming Interested in Tech, 2010](#milestone-becoming-interested-in-tech-2010)
- [Intro to Tech](#intro-to-tech)
- [Milestone: Getting Started in Open Source, 2013](#milestone-getting-started-in-open-source-2013)
- [Announcing TacoFancy](#announcing-tacofancy)
- [One Life Changing Question](#one-life-changing-question)
- [My First Pull Request](#my-first-pull-request)
- [Milestone: Learning the Fundamentals of Maintaining, 2017](#milestone-learning-the-fundamentals-of-maintaining-2017)
- [DjangoCon US: The Conference with a Heart](#djangocon-us-the-conference-with-a-heart)
- [DjangoCon US: The Conference with a Heart](#djangocon-us-the-conference-with-a-heart)
- [DjangoCon US Website](#djangocon-us-website)
- [The Sites I’ve Overseen](#the-sites-ive-overseen)
- [Increase in Number of Contributors](#increase-in-number-of-contributors)
- [“Low Hanging Fruit” PRs](#low-hanging-fruit-prs)
- [That Time I Accidentally Deleted the `dev` branch](#that-time-i-accidentally-deleted-the-dev-branch)
- [I Learned So Much After that](#i-learned-so-much-after-that)
- [How To...](#how-to)
- [Also Became a Mentor](#also-became-a-mentor)
- [OS and Life Lesson: The Mistakes Disappear into the History](#os-and-life-lesson-the-mistakes-disappear-into-the-history)
- [First Tech Talk](#first-tech-talk)
- [Get a Jumpstart on Collaboration and Code Review in GitHub](#get-a-jumpstart-on-collaboration-and-code-review-in-github)
- [Mental Model](#mental-model)
- [My All-Time Favorite Piece of Git Code](#my-all-time-favorite-piece-of-git-code)
- [Quality of Life](#quality-of-life)
- [Second Chances](#second-chances)
- [Eating Dinner With Guido](#eating-dinner-with-guido)
- [Milestone: Becoming a Python Package Maintainer, 2017](#milestone-becoming-a-python-package-maintainer-2017)
- [I Was Hired by Eldarion to Maintain Pinax](#i-was-hired-by-eldarion-to-maintain-pinax)
- [The “Hot Club” Formed: 2007](#the-hot-club-formed-2007)
- [Pinax Was Born: 2008](#pinax-was-born-2008)  
- [How It Began](#how-it-began)
- [How It Began](#how-it-began)
- [How It Was Going, 80 Project and Apps](#how-it-was-going-80-project-and-apps)
- [How It Was Going, GitHub Organization, Global Docs, and Slack](#how-it-was-going-github-organization-global-docs-and-slack)
- [How It Was Going, Sustainability Lacking](#how-it-was-going-sustainability-lacking)
- [Beginner Mindset](#beginner-mindset)
- [Simplified, Self-Service, and Self-Sustaining](#simplified-self-service-and-self-sustaining)
- [Vanilla Django Project](#vanilla-django-project)
- [Vanilla Django Apps](#vanilla-django-apps)
- [Pinax CLI](#pinax-cli)
- [Pinax CLI](#pinax-cli)
- [Pinax CLI](#pinax-cli)
- [`projects.json` File](#projectsjson-file) 
- [Pinax Starter Projects](#pinax-starter-projects)
- [Pinax Apps in Starter Projects](#pinax-apps-in-starter-projects) 
- [Pinax Apps Stand Alone](#pinax-apps-stand-alone)
- [Maintaining Pinax Apps](#maintaining-pinax-apps)
- [Pinax App Codebases](#pinax-app-codebases)
- [Professional Level Configs](#professional-level-configs)
- [Update the Test Matrix](#update-the-test-matrix)
- [pyenv and tox](#pyenv-and-tox)
- [Python/Django Release Notes](#pythondjango-release-notes)
- [Update SemVer Version and Changelog](#update-semver-version-and-changelog)
- [Tag and Publish](#tag-and-publish)
- [Pinax Report Card](#pinax-report-card)
- [Pinax Seems Dead](#pinax-seems-dead)
- [But, Pinax is Still Being Used… A Lot!?](#but-pinax-is-still-being-used-a-lot)
- [But, Pinax is Still Being Used… A Lot!?](#but-pinax-is-still-being-used-a-lot)
- [Pinax Release](#pinax-release)
- [Docs and Standardization](#docs-and-standardization)
- [Community Engagement](#community-engagement)
- [How It’s Going, 20.07 Release](#how-its-going-2007-release)
- [How It’s Going: 21.05 Release](#how-its-going-2105-release)
- [Updating the Test Matrix](#updating-the-test-matrix)
- [Small Improvements](#small-improvements)
- [Documentation](#documentation)
- [Additional Automation](#additional-automation)
- [Creating a Fork](#creating-a-fork)
- [Lessons Learned](#lessons-learned)
- [OS Social Contract](#os-social-contract)
- [The Link Between Django Core Dev and Pinax](#the-link-between-django-core-dev-and-pinax)
- [Centralize Access and Knowledge](#centralize-access-and-knowledge)
- [Managing Volunteer Maintainers](#managing-volunteer-maintainers)
- [Reduce Scope](#reduce-scope)
- [Additional Automation](#additional-automation)
- [Is It Worth It? Yes :)](#is-it-worth-it-yes-)
- [Is It Worth It? Yes :)](#is-it-worth-it-yes--1)
- [Q and A](#q-and-a)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Slides and Script

The script is a general outline and varies somewhat from what was said during the talk.

<table>

<tr><td width="30%">

![Slide 1](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_0.jpg)

</td><td>

### Journey to Maintainer
  
* Greeting
* My name is Katherine Michel. I also go by Kati
* My talk is called “Journey to Maintainer”

</td></tr>

  
<table>

<tr><td width="30%">

![Slide 2](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_1.jpg)

</td><td>

### Affiliations
  
* A few of my affiliations
* Pinax Maintainer/Release Manager part-time for a few years
* I’ve done a bit of open source Python/Django/React consulting to the Wharton School at the University of Pennsylvania (Simpl game simulation framework)
* I’ve been teaching some introductory Python programming through Stanford as a volunteer Section Leader
* DEFNA (Django Events Foundation North America) Board Member 
* DjangoCon US Website Co-Chair
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 3](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_2.jpg)

</td><td>

### Talk Goals
  
* I’m going to talk about
* How I got started in open source and maintaining
* Technical aspects of being a Python package maintainer
* Maintainer report card
* Lessons learned
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 4](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_3.jpg)

</td><td>

### Milestone: Django Was Born, 2003
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 5](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_4.jpg)

</td><td>

### Django is Invented at LJW
  
* Pinax, the library I’m a maintainer of, is built with Django, a Python web development framework
* Django was created at the Lawrence Journal World, in Lawrence Kansas
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 6](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_5.jpg)

</td><td>

### If Only I Had Known
  
* “In one sentence, what advice would you give to your 26 year old self?”
* “Go to the Lawrence Journal World”
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 7](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_6.jpg)

</td><td>

### If Only I Had Known
  
* I was living in Lawrence in 2003
* I was literally driving around the building where Django was being created, yet didn’t know it existed
* I would often frequent the Lawrence Public Library, which was 2 minutes away from the Lawrence Journal World Building

</td></tr>


<table>

<tr><td width="30%">

![Slide 8](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_7.jpg)

</td><td>

### Milestone: Becoming Interested in Tech, 2010
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 9](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_8.jpg)

</td><td>

### Intro to Tech
  
* I decided to move to England
* I earned a Master’s Degree in Project Management at Lancaster University Management School
* As part of that degree program, I had an internship in CFS/Britannia, a financial services company, in the change management department
* At CFS/Britannia, they gave me access to all their current and historical IT project management documentation
* I really enjoyed learning about their computer systems
* I’d never had that sort of access before. It gave me a similar feeling of empowerment as I’ve gotten from open source
* Unfortunately, people being laid off from CFS/Britannia, so there was no chance that I’d be hired there
* But now I was interested in Web Development and Data Science
* And it was only then, in another country, that I learned about Django
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 10](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_9.jpg)

</td><td>

### Milestone: Getting Started in Open Source, 2013
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 11](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_10.jpg)

</td><td>

### Announcing TacoFancy
  
* In 2013, I was using Twitter to learn about and network in the tech industry
* I had signed up for GitHub in April 2013. My account sat unused for 7 months. I didn’t know how to get started.
* I happened to be looking at Twitter. 
* I saw a tweet from a man named Dan Sinker. He had made a really delicious taco meal and decided to start a project on GitHub to share taco recipes. 
* So I clicked on the link and went to the project to take a look. 
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 12](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_11.jpg)

</td><td>

### One Life Changing Question

* There was one question in the project info that changed my life: "Are You New to GitHub But Want to Contribute?" 
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 13](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_12.jpg)

</td><td>

### My First Pull Request
  
* This was the encouragement I needed to get started. 
* I became determined to contribute and submitted my first pull request there.
* I wanted to build on the experience, so I kept using Git and GitHub informally from then on. 
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 14](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_13.jpg)

</td><td>

### Milestone: Learning the Fundamentals of Maintaining, 2017
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 15](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_14.jpg)

</td><td>

### DjangoCon US: The Conference with a Heart
  
* I had spent a lot of time looking through GitHub
* I realized that a lot of conferences are looking for volunteers to maintain their conference websites
* So, I got involved with DjangoCon US
* This is a photo of me with some of the other organizers
* I couldn’t have stumbled upon a more welcoming conference community

</td></tr>


<table>

<tr><td width="30%">

![Slide 16](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_15.jpg)

</td><td>

### DjangoCon US: The Conference with a Heart
  
* The comment on the slide is from my friend Mariatta in her GitHub ReadME Project page
* She mentioned that DjangoCon US was the first ever conference she spoke at and how welcoming it was
* This is a typical kind of comment we receive about DjangoCon US
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 17](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_16.jpg)

</td><td>

### DjangoCon US Website
  
* I became a DjangoCon US website volunteer
* This is another twist in my maintainer story
* At that time, the DjangoCon US website was made with Pinax Symposion
* This was my first introduction to Pinax
* I would later be hired by Eldarion web development agency to maintain Pinax
* Jeff Triplett, the website chair, said at the time that Sympsion was a “Godsend” but also difficult to use due to its complexity
* For example, it was difficult for newcomers like me to contribute
* He had decided to switch to a Jekyll site the following year
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 18](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_17.jpg)

</td><td>

### The Sites I’ve Overseen
  
* I wanted to take my GitHub knowledge to the next level by learning how to be a maintainer
* So, I literally asked the DjangoCon US Chair if I could be a maintainer of the website
* She said “sure” and invited me to be the Website Chair, which I accepted
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 19](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_18.jpg)

</td><td>

### Increase in Number of Contributors
  
* As conflicted as I feel, due to later working for Eldarion
* Jekyll has been great for DjangoCon US
* I was able to learn the fundamentals of being a maintainer, because the Jekyll site was more straightforward
* We were also able to drastically increase the number of contributors from
* From 23 in 2016
* To 65 in 2020
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 20](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_19.jpg)

</td><td>

### “Low Hanging Fruit” PRs
  
* One of the strategies that helped me learn the maintaining process...
* Jeff left the “low hanging fruit” PRs for me to learn on
* I was able to cherry pick the easier PRs to review them with less pressure
* A typo or someone updating a link or their personal info in a markdown file
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 21](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_20.jpg)

</td><td>

### That Time I Accidentally Deleted the `dev` branch
  
* But there is something else that happened that was very impactful to my learning process
* One of the first things I ever did as a maintainer
* I submitted a PR incorrectly
* I realized something was wrong and tried to delete the branch
* What happened instead, was that I deleted the dev branch, which had all of the work in it
* It hadn’t crossed my mind that I could literally delete that branch
* In my mind, this was the worst thing I could possibly do as a maintainer
* I panicked and reached out to the person who had last pushed to the branch, asking him to push the branch again, which he did
* They bent over backwards to assure me that they themselves made mistakes like that and that they should have protected the branch
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 22](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_21.jpg)

</td><td>

### I Learned So Much After that
  
* Learning-wise, it was one of the best things that ever happened to me
* Because it freed me up to learn some much 
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 23](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_22.jpg)

</td><td>

### How To...
  
* Every time I was afraid to do something new, I would remind myself that I had already done the “worst” thing
* I learned how to...
* How to fetch a PR locally
* Run the code
* Push an update to a PR from a fork
* Merge a PR locally
* Push a PR to a `master` branch
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 24](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_23.jpg)

</td><td>

### Also Became a Mentor
  
* I created the new contributing docs
* I helped some newcomers make their first contributions
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 25](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_24.jpg)

</td><td>

### OS and Life Lesson: The Mistakes Disappear into the History
  
* Along the lines of making mistakes
* I feel that open source has changed my life philosophy, for the better
* In the past I was more likely to be paralyzed by the need for perfection
* I’ve become more willing to have a beginner mindset
* My philosophy is that it’s okay to make mistakes, but I expect to keep improving
* I’ve made a lot of progress that way
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 26](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_25.jpg)

</td><td>

### First Tech Talk
  
* Women among DjangoCon US organizers told me that they were afraid to get started in open source
* So, I created a talk about collaboration and code review and gave it for the first time at DjangoCon US 2017
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 27](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_26.jpg)

</td><td>

### Get a Jumpstart on Collaboration and Code Review in GitHub
  
* Not everything had been intuitive for me while learning to use Git and GitHub
* I wanted to explain the “why” of the process and what it literally looks like
* In the hopes that it would make it easier for women in particular to get started
* I’ve given it to several PyLadies groups, as well as to local meetups before Hacktoberfests
* DevICT, PyLadies Remote, PyLadies SWFL
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 28](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_27.jpg)

</td><td>

### Mental Model
  
* In that talk, I explain my mental model for
* What GitHub is and how it works
* “Shared Repository” versus “Fork and Pull” collaboration models
* Show a local development process
* Review pull requests as a maintainer
* Give tips for getting started
* There are several versions in my GitHub Account
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 29](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_28.jpg)

</td><td>

### My All-Time Favorite Piece of Git Code
  
* I also included in the talk my all-time favorite piece of code
* I was really surprised at how difficult it was to find this piece of code
* You would think that a lot of maintainers would need this
* It’s a piece of code to push an update from a local branch to a PR branch in a forked repo
* I could use this to provide a bit of assistance to a contributor when they needed it
  
</td></tr>


<table>

<tr><td width="30%">

![Slide 30](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_29.jpg)

</td><td>

### Quality of Life
  
* Around that time, my quality of life also began to show signs of improving
* I had started to acquire a technical skill set
* I would soon have better pay than ever before
* I was beginning to be able to travel to conference
* Meet smart, interesting people building cool things (check out my Twitter lists)
* Travel to cool places
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 31](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_30.jpg)

</td><td>

### Second Chances
  
* I also began to have some second chances
* Although I may not have been at the Lawrence Journal World at the right time
* I’ve had the chance to become friends with some of the LJW people who were there
* Here I am at DjangoCon US 2018 on a “State of Django panel” moderated by Simon Willson, one of the Django co-creators
* And Jeff Triplett and Frank Wiles, early Django developers and users as LJW staff
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 32](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_31.jpg)

</td><td>

### Eating Dinner With Guido
  
* I’ve also had the chance to eat dinner with Guido, the creator of Python programming language
* This was at PyCascades 2020
* He told us some stories about the early days of Python
* It was a magical evening
* I directly attribute these kinds of experiences to open source
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 33](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_32.jpg)

</td><td>

### Milestone: Becoming a Python Package Maintainer, 2017 
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 34](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_33.jpg)

</td><td>

### I Was Hired by Eldarion to Maintain Pinax
  
* In the fall of 2017, based on my experience as a DjangoCon US 2017 maintainer, I was hired to work on Pinax
* Pinax is an open-source library of reusable Django starter projects, apps, and themes for building websites. 
* It kind of sounds funny for me to describe Pinax that way, because over time, I’ve learned much more about the history surrounding it
* I’ll always have a special place on my heart for Eldarion because they gave me an opportunity when it was difficult for me to find one
* Having said that, just as Jeff Triplett said about using Pinax for the DjangoCon US site, Pinax was a “Godsend” for me, but I was naive to the complexity of it
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 35](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_34.jpg)

</td><td>

### The “Hot Club” Formed: 2007
  
* A bit of background about Pinax
* When I was hired, it had been around 10 years since the Pinax idea had been born
* Django had been open sourced in 2005
* At PyCon 2007, some Django enthusiasts had formed a group called the “Hot Club of France,” named after Django Reinhardt’s band. 
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 36](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_35.jpg)

</td><td>

### Pinax Was Born: 2008
  
* In March 2008, at PyCon US in Chicago, they began sprinting on Pinax
* They were creating Pinax to solve their own problem
* They had found themselves reusing some of the same code patterns while building websites with Django
* So they began to abstract these patterns into reusable Django starter projects, apps, and themes
* In September, the first ever DjangoCon US took place
* James Tauber one of the original Pinax authors, gave a talk about this new community called Pinax
* He said they wanted to create a reusable web development library that would make choices and compromises
* This library would enable them to focus on the features at the top of the stack
* That way, they could go from website idea to realization quickly, instead of re-inventing the wheel
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 37](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_36.jpg)

</td><td>

### How It Began
  
* James talked about his own site Quisition
* Even though it was a flashcard site, much of its functionality had nothing to do with flashcards
* This type of functionality had begun to be abstracted into reusable Pinax apps
* A lot of it was the kind of functionality you would find in social media sites
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 38](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_37.jpg)

</td><td>

### How It Began
  
* So what was the state of Pinax when I was hired?
* It’s quite common, from the very beginning until now, for people to discover Pinax and say “it’s everything they ever dreamed of”
* On this slide is one of the very early tweets about Pinax… someone says “Pinax is every idea I’ve ever had.”
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 39](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_38.jpg)

</td><td>

### How It Was Going, 80 Project and Apps
  
* By 2017, Pinax had grown to be a large group of professionally-quality, interdependent Django projects and apps
* This included starter projects with Pinax apps pre-installed and a command line interface to install them
* This also includes sophisticated testing, packaging, and continuous integration configurations
* The Pinax GitHub organization alone has around 80 repos in it
* This slide includes many of the more popular ones
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 40](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_39.jpg)

</td><td>

### How It Was Going, GitHub Organization, Global Docs, and Slack
  
* In addition to the GitHub organization
* Pinax now had a global docs site and a Pinax Slack channel for community and support
* There were also app-specific docs in individual repos
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 41](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_40.jpg)

</td><td>

### How It Was Going, Sustainability Lacking
  
* But… sustainability was lacking
* Many of the original authors had moved on
* Without a strategy in place to make Pinax as easy as possible to maintain, the maintainers began to suffer burnout. 
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 42](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_41.jpg)

</td><td>

### Beginner Mindset
  
* There has been a disconnect between their very high skill level of the authors and the beginner mindset that newcomers may have
* Some of the authors knew so much that they couldn’t go back down to a beginner level anymore
* It was hoped that I would have a valuable perspective as a newcomer to Pinax and could bridge the gap
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 43](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_42.jpg)

</td><td>

### Simplified, Self-Service, and Self-Sustaining
  
* The goal in general was to work to make things simpler and self-service
* As a result, newcomers, contributors, and maintainers could help themselves
* And therefore, create a culture that could sustain itself
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 44](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_43.jpg)

</td><td>

### Vanilla Django Project
  
* I’m going to switch gears a bit to GitHub and the local dev environment and explain how Pinax works
* In your local dev environment, if you are starting a vanilla Django project...
* You will need to have Django installed and you would normally be using a virtual environment
* Run the ```django-admin startproject``` command in the terminal to start a project
* The project contains the global settings and other configurations for your site
* The project template files populated in the directory come from within the Django package
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 45](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_44.jpg)

</td><td>

### Vanilla Django Apps
  
* You would then run an additional command to add one or more apps to your project
* Each app contains special functionality (for example a `blog` app for a blog part of your website)
* The app template files populated also come from within the Django package
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 46](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_45.jpg)

</td><td>

### Pinax CLI
  
* With Pinax, the Pinax CLI (command line interface) can be installed
* You can use commands to get info about Pinax (such as a list of starter projects or apps)
* Pinax starter projects are basically custom Django projects
* They already have some functionality built in and by using them, you do not have to start from scratch using a vanilla Django project
* The same with Pinax Apps
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 47](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_46.jpg)

</td><td>

### Pinax CLI
  
* You can also use the pinax-cli to install a Pinax starter project instead of the vanilla Django project
* There is a special pinax-cli command to do this `pinax start <pinax-starter-project> <your-project>
* When the pinax-cli runs this command
* The pinax-cli uses the same ```startproject``` command used to install a vanilla Django project
* But it’s called from within the pinax-cli codebase
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 48](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_47.jpg)

</td><td>

### Pinax CLI
  
* The starter project URL is passed in as a parameter
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 49](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_48.jpg)

</td><td>

### `projects.json` File
  
* The URL leads to a `projects.json` file that provides the tar file address in the Pinax Starter Projects GitHub repo
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 50](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_49.jpg)

</td><td>

### Pinax Starter Projects
  
* Pinax Starter Projects are in one repo
* Each starter project is in an individual branch
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 51](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_50.jpg)

</td><td>

### Pinax Apps in Starter Projects
  
* Each starter project contains the relevant Pinax apps, to be installed from PyPI (The Python Package Index)
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 52](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_51.jpg)

</td><td>

### Pinax Apps Stand Alone
  
* Alternatively, Pinax apps can be used independently of any Pinax starter project
* You can find them by searching “pinax” on PyPI
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 53](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_52.jpg)

</td><td>

### Maintaining Pinax Apps
  
* As far as maintaining Pinax Apps goes… 
* GitHub Flow workflow
* CalVer at release-level (year.month)
* SemVer at app-level (major.minor.patch)
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 54](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_53.jpg)

</td><td>

### Pinax App Codebases
  
* Each Pinax app codebase lives in a GitHub repo
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 55](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_54.jpg)

</td><td>

### Professional Level Configs
  
* Each app repo has professional level configurations used to keep the code up-to-date
* CircleCI is there for continuous integration
* `setup.py` contains packaging configurations
* `tox` is for testing the Python/Django versions matrix
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 56](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_55.jpg)

</td><td>

### Update the Test Matrix
  
* When we do a release, we update the test matrix to support the latest versions of Python and Django
* In my release plan, I document some test matrix boilerplate that I will copy and paste into the app files
* CircleCI Boilerplate
* tox Boilerplate
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 57](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_56.jpg)

</td><td>

### pyenv and tox
  
* The process is that… 
* I clone the Pinax app repo locally, create a new branch
* Update the test matrix in the branch
* There is a tool called pyenv that can be used to install multiple global Python versions locally
* When tox is run, it can use these global versions to check the compatibility of the Pinax App code against the new Python/Django versions
* When there is an incompatibility, tox will show you the error in red
* When all of the tests pass… you will get all green at the end
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 58](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_57.jpg)

</td><td>

### Python/Django Release Notes
  
* While you are troubleshooting to fix these incompatibilities
* The Python/Django release notes tell you what changes have been made to the Python/Django codebase in the release
* You can use the release notes to figure out what updates to make for compliance
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 59](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_58.jpg)

</td><td>

### Update SemVer Version and Changelog
  
* When all of your test matrix and other updates have been made
* You will want to update SemVer Version in the setup.py
* As well as the versions throughout the setup.py metadata and README
* Update the Changelog in the README
* These are some of the various pieces of metadata
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 60](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_59.jpg)

</td><td>

### Tag and Publish
  
* Then go to the “tags” area of the app’s GitHub repo
* Draft a new release
* Including a link to the Changelog
* Run a process locally to package the app
* I have documented this process in the .github repo in the RELEASE.md file
* And publish the package to PyPI (Python Package Index)
  
</td></tr>
  

<table>

<tr><td width="30%">

![Slide 61](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_60.jpg)

</td><td>

### Pinax Report Card
  
* A Pinax report card
* GitHub Open Source Guide: “A Checklist Before You Contribute” 
* The lack of activity in Pinax is a major problem
https://opensource.guide/how-to-contribute/#a-checklist-before-you-contribute
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 62](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_61.jpg)

</td><td>

### Pinax Seems Dead
  
* Pinax seems dead
* This has gotten worse during Covid, due to me being laid off
* The ToDo group guide has a section about “Shutting Down an Open Source Project”
* In it, the authors describe what a “dead project” is like
* The description sounds like Pinax
https://github.com/todogroup/guides/blob/master/shutting-down-an-open-source-project.md
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 63](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_62.jpg)

</td><td>

### But, Pinax is Still Being Used… A Lot!?
  
* But Pinax is still being used, a lot
* I had no expectation about pinax-app stats
* Looking at Snyk stats… 
* One package (pinax-ratings) has 1045 downloads per week and the last release was by far the most popular
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 64](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_63.jpg)

</td><td>

### But, Pinax is Still Being Used… A Lot!?
  
* I was skeptical, so I did a query through BigQuery (query recommended by PyPA- Python Packaging Authority)
* pinax-ratings has 27,550 downloads over 6 months!
* It’s not on the scale of famous packages, but still made my day!
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 65](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_64.jpg)

</td><td>

### Pinax Release
  
* Releases are happening more regularly now
* Which means the test matrix and code are updated
* This keeps the code more secure
* Plus, access to new features
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 66](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_65.jpg)

</td><td>

### Docs and Standardization
  
* While I was an active maintainer… I’ve worked to fix some of the critical problems Pinax has
* Documented the tribal knowledge
* Made one source of documentation, made it extremely easy to find, and use
* Created detailed release and maintainer docs
* Created Community Health Files, including Issue and PR Templates
* Chose one configuration approach and implemented across projects
   
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 67](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_66.jpg)

</td><td>

### Community Engagement
  
* Going back to this problem of inactivity
* Lack of engagement with individuals and community
* While I was an active maintainer...
* Reduced the backlog of existing issues and PRs and caught up on engaging with current issues and PRs
* Before the release last year, I was able to close or merge nearly 300 issues and PRs (many were “problem” ones”)
* Wrote more blog posts about plans and progress, and publicize them
* Through my writing, I was able to attract some assistance that was crucial in completing the last release
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 68](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_67.jpg)

</td><td>

### How It’s Going, 20.07 Release
  
* There was an 18.01 release… I had a mentor who me taught some of the fundamentals of being a release manager
* Unfortunately, my mentor was laid off after that
* In July 2020, I found it within myself to oversee the completion of an important Pinax release. 
* Around 28 apps were included and we notably dropped support for Python 2.7
* It was a huge milestone for me, personally and professionally. Not only did I initiate the release, but I managed the end-to-end process. I created the release plan, oversaw the work of others, updated 10 apps myself, merged all of the PRs, and tagged and published the packages. 
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 69](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_68.jpg)

</td><td>

### How It’s Going: 21.05 Release
  
* I’ve been working on the 21.05 release recently
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 70](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_69.jpg)

</td><td>

### Updating the Test Matrix
  
* It’s time to update the Python/Django test matrix
* Unfortunately, there don’t seem to be many changes to make, which I’m disappointed about
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 71](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_70.jpg)

</td><td>

### Small Improvements
  
* Fix `setup.py test` deprecation
* Fix isort deprecations
* Add Black formatter
* Find best practices like Twine
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 72](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_71.jpg)

</td><td>

### Documentation
  
* Global documentation is in need of improvement
* App- specific documentation should be double-checked
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 73](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_72.jpg)

</td><td>

### Additional Automation
  
* Automation that was not implemented in the last release can be implemented now
* GitHub Action that runs tox
* GitHub Action to auto-publish to PyPI upon tagging
* I’m not sure if I’m going to go forward with this due to lack of engagement from other maintainers
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 74](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_73.jpg)

</td><td>

### Creating a Fork
  
* Myself and another contributor would like to update the Pinax Starter Projects and Pinax CLI
* It has been suggested by a Pinax organization owner that we fork them, so perhaps we will
* I’d like to get the whole system working properly, if nothing else, as a learning experience
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 75](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_74.jpg)

</td><td>

### Lessons Learned
  
* I want to talk about some lessons learned… 
* About how to make a community self-sustaining
* Unfortunately, I fear that Pinax is never going to be healthy and thriving
* This is a sad subject for me
* Pinax has attracted some negativity
* Yet, there is so much generosity involved on the part of the authors
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 76](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_75.jpg)

</td><td>

### OS Social Contract
  
* Brett Cannon (Python Core Dev) has talked about the open source “social contract”
* Open source maintainers owe the community quite literally nothing
* The Pinax authors didn’t have to open source their code and maintain it
* They didn’t have to answer the countless questions they answered
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 77](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_76.jpg)

</td><td>

### The Link Between Django Core Dev and Pinax
  
* Something that I think is useful to know about this situation is that many of the Pinax authors were Django core devs
* Pinax has some of the same challenges as the Django core project
* It’s my understanding that at some point, the Pinax maintainers had hoped to merge Pinax into the Django core codebase, but it didn’t happen
* On the slide is an example of a person who was incredibly generous in contributing to Django Core and Pinax
* He commented back then about burnout
* I know that they also had fun, but these lessons learned are about how to make open source healthier for people like this
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 78](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_77.jpg)

</td><td>

### Centralize Access and Knowledge
  
* One of the problems that happened
* There were individuals who championed projects
* Maybe one person had project knowledge and access (repo access, PyPI access)
* If the person would abandon it, maybe they would not hand access/knowledge over to someone else
* Contributors would come along and open issues and PRs, not knowing that there was no leadership
* It would have been better in my opinion, to have had a policy of centralizing all of the access
* And to be willing to hand access over to someone new
* Another flavor of this problem would be when a maintainer would create a unique solution to a problem and be the only person with knowledge and access
* If they would lose interest, others would be blocked from picking up where that person left off
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 79](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_78.jpg)

</td><td>

### Managing Volunteer Maintainers
  
* Ideally, volunteer maintainers would be brought on when there is more traffic, to maintain the momentum
* Give selective permissions
* Protect branches
* Require reviews
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 80](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_79.jpg)

</td><td>

### Reduce Scope
  
* Mark repos as deprecated
* Archive repos
* Disable issues
* Communicate that the code is maintained sporadically
  
</td></tr>

  
<table>

<tr><td width="30%">

![Slide 81](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_80.jpg)

</td><td>

### Additional Automation
  
* GitHub Actions
* GitHub Apps
* Probot: https://probot.github.io/
* Probot is a place to get novel ideas about what could be automated
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 82](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_81.jpg)

</td><td>
  
### Is It Worth It? Yes :)
  
* As I was working on this presentation and thinking about some of the heavy subject matter…
* Maintainer Week was happening
* I saw this tweet from Mfon… his contributions were critical in helping me complete the 20.07 release
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 83](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_82.jpg)

</td><td>
  
### Is It Worth It? Yes :)
  
* Seeing the difference my work had made to him and knowing he considers me to be a very good friend
* I almost lost it when I saw his tweet
* What he said immediately made it worth it
* I suddenly realized...
* At the heart of open source… are the relationships I’ve formed with people
* Which I’ll have for the rest of my life
  
</td></tr>
  
  
<table>

<tr><td width="30%">

![Slide 84](https://speakerd.s3.amazonaws.com/presentations/41cbcd6d09cc4966b4439051ac3db2a5/slide_83.jpg)

</td><td>

### Q & A
  
* I am now ready to take questions in the Q & A
  
</td></tr>
  
  
</table>

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Attribution

The style of this transcript is heavily inspired by:

* Ana Balica's ([Twitter](https://twitter.com/anabalica), [GitHub](https://github.com/ana-balica)) transcript of her [Humanizing among coders](https://ana-balica.github.io/2017/05/28/humanizing-among-coders/) keynote for [PyCon CZ 2016](https://cz.pycon.org/2016). 
* Honza Javorek's ([Twitter](https://twitter.com/honzajavorek), [GitHub](https://github.com/honzajavorek)) transcript of Anna Ossowski's ([Twitter](https://twitter.com/OssAnna16), [GitHub](https://github.com/OssAnna16)) keynote [Be(Come) A Mentor! Help Others Succeed!](https://github.com/honzajavorek/become-mentor) for [PyCon CZ 2017](https://cz.pycon.org/2017/). 

Thank you!

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Contact Kati

* Email: kthrnmichel@gmail.com
* GitHub: https://github.com/KatherineMichel
* Twitter: https://twitter.com/KatiMichel

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

## Copyright

© 2021 to Present Katherine Michel. All Rights Reserved.
