---
layout: essay
type: essay
title: Brewing the Inescapeable Meteor IPA Beer
date: 2017-03-23
labels:
  - Software Engineering
  - Frameworks
---
## By Clark DeNunzio

<img class="ui centered medium image" src="../images/meteor-logo.png">

[Meteor.JS](meteor.com)

<hr>

Meteor in general is a different flavour of HTML, CSS, and JavaScript but like with any framework these skills can easily be moulded into the correctly functioning versions of themselves. Overall, working with Meteor has been a joy compared to other frameworks, and I'm impressed with it's out-of-the-box functionality for sure. The only problem is that it's exceptionally heavy-weight... I'm talking super-massive, like orders of orders of magnitude in comparison to other frameworks. For what they are making you buy, it better work out-of-the-box, and it better have intuitive commands. Luckily Meteor actually delivers these entry points, and using the software is actually graceful, once you overlook the gigabytes of Harddrive space being consumed by a measly JavaScipt app.

It's obvious that Meteor isn't going to be for everything because of it's inordinate use of system resources, but it's still cool, and worth considering for production level applications; for a hobbyist, not so much, as the costs of deploying the application are simply too great. Just developing simple tutorials on my local machine has consumed 10 gigabytes of Harddrive space, so I cannot begin to think of the complexity costs of using Meteor at production scale. The framework comes with some interesting features that may explain it's size. Hot-Reloading and distributed miniMongo sessions are, for sure, some worthwhile pieces of technology to take advantage of with Meteor. 

<hr>

Hot-Reloading: 

  In line the Meteor server will restart and adjust to changes made in the source code. Furthermore, the Meteor server will also ouput intuitive error messages to help the developer debug the application back to a working state. Meteor crashes gracefully and has several nuances to let you know that something is not rigged up properly. Such as stylesheets breaking until a page is fully qualified with working routes. This saves an incredible amount of time, believe it or not.

<hr>

Mini-Mongo: 

  Meteor uses MongoDB as it's backend leveraging a service called miniMongo in use with the actual Application itself. MiniMongo is a localized session of the Application's MongoDB database that is active among all the sessions of all the users on the Application. Meteor has a centralized location of MongoDB that it will automatically tabulate and, to preserve the integrity of the centralized MongoDB, it will issue sessions of miniMongo to the users with access to just the collections they need. Once the user closes their session, MongoDB will then recursively add the changes of their miniMongo session back into the centralized MongoDB and redistribute the changes to the remaining miniMongo sessions. This powerful tool shows of the asyncronous paradigm off JavaScript.

<hr>

Other than that, it's just another JavaScript framework among the hundreds of new JavaScript frameworks that are being released every other day. You read the docs, do some tutorials (a.k.a. copy-pasting code from a template), and put it on your resume. Investing to learn a framework beyond that just doesn't make sense, as you can google for yourself and read about at least ten new alternatives to any framework out there.


JavaScript is so cluttered I'm beginning to wonder, who cares anymore? For JavaScript in 2017, congruently with the rise of the Trump administration, it's time to take a serious evaluation of the current situation. If it only takes me about 45 minutes of raw, honest effort to translate my skills to a new framework, then how can it be argued that said framework was even necessary? How many punctuationMark.JS or sciFiWord.JS do we need before we realize that it's just developers desperately trying to pad their social media accounts? Furthermore, what are they developing these hundreds of "frameworks" for; if they are only using them to make uninspired clones of preexisting Apps that were never really that innovative to begin with? It seems like fear of displeasing an imaginary grey-haired corporate executive is the only thing driving frontend developers these days, which leads me to conclude that learning "frameworks" is nothing more than beating a dead horse. 
