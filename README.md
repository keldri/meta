## About Apartment Therapy Media

At Apartment Therapy Media we publish two lifestyle sites [**Apartment Therapy**](http://ApartmentTherapy.com) and [**The Kitchn**](http://TheKitchn.com). Our mission is to help people make their homes more beautiful, organized and healthy by connecting them to a wealth of resources, ideas and community online.

[**WE ARE HIRING!**](http://www.apartmenttherapy.com/jobs)
## Who We Are

Our engineering & design teams currently consist of 6 (incredibly talented, friendly & collaborative) engineers (4 senior, 2 junior), 2 web designers, and 1 product manager.  We're currently hiring a second [product manager](http://www.apartmenttherapy.com/product-manager-224987) and fifth [senior developer](http://www.apartmenttherapy.com/web-designer-224989).

Our team (and much of the company) **works remotely**. **Slack** has quickly become our critical communication channel. We make heavy use of Slack integrations including our own bot to manage code deployment & staging environments.

## How We're Organized

We've reached a critical growth phase as a team. We have just split our single team into separate self-sufficient squads with independent missions, heavily inspired by the [Spotify model](https://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/). Our current open positions will fill out these squads and our hiring plan into 2016 includes creating 1-2 more squads.

Each squad has its own mission, related initiative pipeline (for future planning purposes) and issue tracker (currently Trello boards) for tracking and managing ongoing work. We currently work in **two week sprints**.

We're currently experimenting with models to more deeply integrate product and design work into our workflow and plan to run a pilot [design sprint](http://www.gv.com/sprint/) in the near future.

## How We Work - Engineering

We use **git** and **GitHub** for our projects. We use GitHub's **pull requests for code review**. We're currently tracking stories in **Trello**. 

We practice **continuous integration**. We run our automated tests through our build system (CircleCI) and have invested heavily in tools to make deploying new code ordinary and routine. We deploy code every day.

We currently use **New Relic**'s suite of tools for application monitoring. We catch exceptions with **Airbrake**, and monitor front-end performance with **SpeedCurve**.

We deploy to **Heroku**, finding the cost-to-performance ratio worth the tradeoffs.  

## Stack & Tools

Our two primary applications (a custom CMS and custom Community stack) are built with **Ruby on Rails** (4.1) making heavy use of **varnish (via Fastly), postgres, redis, unicorn and elasticsearch**. We also run a custom image service on **Sinatra**.

Our application architecture is evolving into a back-end that primarily serves as an API for rich client-side code built with **React.js** and the **Flux** architecture. 

## Open Source Code

We recently extracted and published a couple of gems we use in our color-based image search, which gives a little peek behind these scenes of some of the back-end code we write:
* [multicolor](https://github.com/apartmenttherapy/multicolor): an opinionated library for [TinEye's fabulous MulticolorEngine](http://services.tineye.com/MulticolorEngine)
* [color-rgb](https://github.com/apartmenttherapy/color-rgb): a set of utilities to help with dealing with RGB colors

## Our "Joel Test" Answers

* Do you use source control? _Yes. git & GitHub._

* Can you make a build in one step? _Yes. This is automated with CircleCI. Deploys to staging & production environments are also a single command._

* Do you make daily builds? _Yes, this is continuous and automated._

* Do you have a bug database? _Yes, we track bugs in Trello._

* Do you fix bugs before writing new code? _Yes, in most cases._

* Do you have an up-to-date schedule? _Sort of. We engage in an agile (small a) process to track & estimate current & near term work & priorities._

* Do you have a spec? _Usually and we're getting better at better intitiative and story definition._

* Do programmers have quiet working conditions? _Yes. We all work from home._

* Do you use the best tools money can buy? _Yes._

* Do you have testers? _No._

* Do new candidates write code during their interview? _Yes._

* Do you do hallway usability testing? _Yes, though our "hallways" are on Slack._

[WE ARE HIRING](http://www.apartmenttherapy.com/jobs).
