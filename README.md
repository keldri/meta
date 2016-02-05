## About Apartment Therapy Media

At Apartment Therapy Media we publish two lifestyle sites [**Apartment Therapy**](http://ApartmentTherapy.com) and [**The Kitchn**](http://TheKitchn.com). Our mission is to help people make their homes more beautiful, organized and healthy by connecting them to a wealth of resources, ideas and community online.

[**WE ARE HIRING!**](http://www.apartmenttherapy.com/jobs)

## About the Product Team

Our Product Team currently consists of 9 (incredibly talented, friendly & collaborative) people: 6 engineers (3 senior / 1 mid-level / 2 junior), 2 designers, and a product manager. We're currently hiring a second [product manager](http://www.apartmenttherapy.com/product-manager-224987).

Our team **works remotely**, as does much of the company. **Slack** has quickly become our critical communication channel. We make heavy use of Slack integrations including our own bot to manage code deployment & staging environments.

## How We’re Organized

We recently reached a critical growth phase as a team. We have just split our single team into separate self-sufficient **squads**, heavily inspired by the [Spotify model](https://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/). Each squad has its own independent mission, initiative pipeline, and issue queue to track and manage ongoing work. Our current open positions will fill out these squads and in 2016 we plan to fill 1-2 more squads with new hires.

We follow a loose, "small a" agile methodology. We work on high-level initiatives in **two week sprints**. Each sprint starts with a planning session and ends with a retrospective, with a check-in halfway through. We also do a daily "Slack-Up" in chat with what we plan to accomplish each day.

We're currently experimenting with models to more deeply integrate product and design work into our workflow and plan to run a pilot [design sprint](http://www.gv.com/sprint/) in the near future.

## How We Work

We use **git** and **GitHub** for our projects. All non-trivial code is **peer-reviewed** using GitHub's pull requests. We're currently tracking stories in **Trello**. 

We practice **continuous integration**. We run our automated tests through our build system (**CircleCI**) and have invested heavily in tools to make deploying new code ordinary and routine. We deploy code every day.

We currently use **ScoutApp** and **New Relic**'s suite of tools for systems and application monitoring. We catch exceptions with **Airbrake**, monitor front-end performance with **SpeedCurve**, and track custom metrics with **Librato**.

We deploy to **physical hardware**, finding the cost-to-performance ratio worth the tradeoffs (though we have experience operating VPS deployments and are evaluating PaaS alternatives). We currently use **puppet** for configuration management.

## Stack & Tools

Our two primary applications (a custom CMS and custom Community stack) are built with **Ruby on Rails** (4.1) making heavy use of **varnish**, **postgres**, **redis**, **unicorn** and **elasticsearch**. We also run a custom image service on **Sinatra** and two small, non-critical services built with **go**.

Our application architecture is evolving into a back-end that delivers core content and provides an API for rich client-side code layered on top with **React** and a custom vanilla **Flux** implementation. We are experimenting with **GraphQL** and **Relay** for more integrated data management.

## Open Source Code

We recently extracted and published a couple of gems we use in our color-based image search, which gives a little peek behind these scenes of some of the back-end code we write:
* [multicolor](https://github.com/apartmenttherapy/multicolor): an opinionated library for [TinEye's fabulous MulticolorEngine](http://services.tineye.com/MulticolorEngine)
* [color-rgb](https://github.com/apartmenttherapy/color-rgb): a set of utilities to help with dealing with RGB colors

## Our [Joel Test](http://www.joelonsoftware.com/articles/fog0000000043.html) Answers

* Do you use source control?  
  **Yes, git & GitHub.**

* Can you make a build in one step?  
  **Yes. This is automated with Jenkins. Deploys to staging & production environments are also a single command.**

* Do you make daily builds?  
  **Yes, this is continuous and automated.**

* Do you have a bug database?  
  **Yes, we track bugs in Trello.**

* Do you fix bugs before writing new code?  
  **Yes, in most cases.**

* Do you have an up-to-date schedule?  
  **Sort of. We engage in a "small a" agile process to track and estimate current and near-term work and priorities.**

* Do you have a spec?  
  **_Usually, and we're constantly improving our intitiative and story definitions.**

* Do programmers have quiet working conditions?  
  **Yes. We all work from home.**

* Do you use the best tools money can buy?  
  **Yes.**

* Do you have testers?  
  **No.**

* Do new candidates write code during their interview?  
  **Yes.**

* Do you do hallway usability testing?  
  **Yes, though our "hallways" are on Slack.**
