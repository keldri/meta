## About Apartment Therapy Media

At Apartment Therapy Media we publish the lifestyle sites [**Apartment Therapy**](http://www.apartmenttherapy.com) and [**Kitchn**](http://www.thekitchn.com) for an audience of 29+ million monthly readers. Our mission is to help people make their homes more beautiful, organized and healthy by connecting them to a wealth of resources, ideas and community online.

[**WE ARE HIRING!**](http://www.apartmenttherapy.com/jobs)

## Who We Are

Our Product team consists of 11 talented, friendly & collaborative people — 7 engineers, 2 web designers, and 2 product managers. We are responsible for leading, building, and iterating on all web products at Apartment Therapy Media.

Our team (and much of the company) **works remotely**. The whole company communicates through **Slack** all day, and we make heavy use of integrations including our own bot to manage code deployment & staging environments.

## Team Culture

At our size it’s necessary to have some structure over the team, but we still try our best to maintain a **flat culture**. Artificial boundaries get in the way of good work, so we’re as permissive as practical with our code, tools, and processes. We also want our team to embody a great **diversity of ideas** so we strive to create space for everyone's thoughts and opinions to be considered.

We want to be a team that’s built on **mutual respect**. When we have a big success, we share in it together. When we have a misstep, we use **blameless postmortems** to learn from it. In short — no heroes, no egos.

## How We’re Organized

Over the past year we’ve been working in small cross-functional **squads**, heavily inspired by the [Spotify model](https://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/). Each squad has its own mission, related initiative pipeline and issue tracker to manage ongoing work. Despite this division of work, we maintain a cohesive team environment and strongly encourage cross-squad collaboration and support.

We’re continually experimenting with our processes, and just recently invited stakeholders from other departments into our squads to encourage more company-wide collaboration. These non-Product squad members sketch with us, work alongside us, and as a result share ownership of what we’re building together.

## Processes & Workflow

We follow an informal agile (small “a”) process. Our **two-week sprints** begin with individual squad planning sessions and end with a team-wide retrospective. We have a check-in meeting in the middle and daily **“Slack-Up Meetings”** to keep our work aligned and on track.

Our squads have a lot of **autonomy** over how they work. In general, each squad is driven by high-level goals and can fulfill those goals as they best see fit. Sometimes the next steps for a squad are obvious, but we’ve also tried [**design sprints**](http://www.gv.com/sprint/) to better understand the problems and possible solutions ahead of us.

We’re currently working on integrating **data analysis** and **KPI dashboards** more deeply into our process so we can rapidly iterate based on real-world learning. As part of this work we’re playing with **feature toggles** so we can build and test new features directly in our production environment.

## Stack & Tools

Our two primary applications (a custom CMS and custom Community stack) are built with **Ruby on Rails** (4.2) making heavy use of **varnish (via Fastly), postgres, redis, unicorn and elasticsearch**.

Our application architecture is evolving into a back-end that primarily serves as an API for rich client-side code built with **React.js** and a house implementation of the **Flux** architecture. Our front-end assets are compiled through **webpack** using **Babel**, **SASS**, and other modern tooling. We recently implemented **server-rendering of React components** to share UI code between our server-generated HTML and dynamic features.

We use **git** and **GitHub** for our projects. All non-trivial code is reviewed in GitHub **pull requests**. We’re currently tracking our work in **Trello**.

We practice **continuous integration**. We run our automated tests through our build system (CircleCI) and have invested heavily in tools to make deploying new code ordinary and routine. We deploy code every day.

We currently use **New Relic**’s suite of tools for application monitoring. We catch exceptions with **Airbrake**, and monitor front-end performance with **SpeedCurve**.

We deploy to **Heroku**, finding the cost-to-performance ratio worth the tradeoffs.

## Open Source Code

We have a few small open-sourced projects and hope to continue open-sourcing more of our work in the near future. Please feel free to contribute!

* [react-pinboard](https://github.com/apartmenttherapy/react-pinboard): a React component to display content in a responsive Pinterest-style layout
* [multicolor](https://github.com/apartmenttherapy/multicolor): an opinionated Ruby gem for [TinEye’s fabulous MulticolorEngine](http://services.tineye.com/MulticolorEngine)
* [color-rgb](https://github.com/apartmenttherapy/color-rgb): a set of utilities to help with dealing with RGB colors in Ruby

## Our [“Joel Test”](http://www.joelonsoftware.com/articles/fog0000000043.html) Answers

* **Do you use source control?**  
  Yes. git & GitHub.

* **Can you make a build in one step?**  
  Yes. This is automated with CircleCI. Deploys to staging & production environments are also a single command.

* **Do you make daily builds?**  
  Yes, this is continuous and automated.

* **Do you have a bug database?**  
  Yes, we track bugs in Trello and have a dedicated squad for critical bugfixes and code cleanup.

* **Do you fix bugs before writing new code?**  
  Yes, in most cases.

* **Do you have an up-to-date schedule?**  
  Yes. Our squads have clear near-term goals.

* **Do you have a spec?**  
  Yes. We also have relevant stakeholders actively working with us.

* **Do programmers have quiet working conditions?**  
  Yes, if you like! We’re almost all working from home so you can crank the radio as loud as you want.

* **Do you use the best tools money can buy?**  
  Yes.

* **Do you have testers?**  
  No.

* **Do new candidates write code during their interview?**  
  Yes.

* **Do you do hallway usability testing?**  
  Yes, though our “hallways” are on Slack.
