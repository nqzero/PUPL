# PUPL - Payed Use Permissive License - FAQ

### are you a lawyer ?
no

### how do i use this license ?
choose a strike price.
this is the maximum that anyone will ever need to pay you to use your software on 1 core for 1 year.
add a note "this software is licensed under the terms of PUPL from nqzero, with a per-annum strike price of $100".



### has a lawyer signed off on this license ?
no.
when i get the general idea hashed out i may pay a lawyer to look at it.
i guess my inspiration is the json license - it's plain english
("The Software shall be used for Good, not Evil")
[was good enough to get IBM to "negotiate"](http://dev.hasenj.org/post/3272592502/ibm-and-its-minions)


### why not free or open source software ?
i've written a database software and i'm hoping to use this license for it

ultimately, i'm hoping to return a profit on the time i've invested and continue to invest in creating the database. for some products, open source can be a profitable path, typically by charging for support or hosting the software or as marketing for consulting services. however, for some useful products, these paths don't seem to work well even though the software product is widely used. this license is an assurance that if my software is widely adapted, i'll make money

further, it enables me to develop the software to maximize usefulness, as opposed to maximize the need for support services

i don't know that this license is the right one, but i feel there exists potential for a license in this space
that balances creator profits with user freedom


### why not a (traditional) proprietary license ?
such licenses discourage adoption and use by making it hard for a user or ISV to predict future costs. due to the investment in adopting a software or building products on it, users and ISVs are locked into it. the developer can increase the price of additional copies of the software or charge arbitrary prices far above actual costs for adding features or fixing bugs (even security bugs). while i don't intend to charge prices in this way, it would be foolish for a prospective customer to invest in software without assurances that the developer won't abuse this investment in the future. this license attempts to provide that assurance and stimulate adoption


### if my business adopts this software, can the price increase later (if my usage stays the same) ?
if you pay the sale (as opposed to full) price, then the sale price could increase
if you pay the full price, then each year you use the product you'll pay that same price (even with lapses)
if you pay the lifetime price, then you don't have to pay again

### if my usage increases, will additional use-licenses cost more than i paid initially ?
the price may increase. however, you'll never pay more than the strike price for a per-annum use-license. in addition, if you paid full price for a per-annum (without lapses) or a lifetime use-license, you're entitled to purchase 4 additional use-licenses at that same price. these rules are intended to protect you if you scale


### should my company (an end user) pay full price or the sale price
if you think that you're likely to use the software long term, then you may want to pay full price. your investment in learning the software and building tools upon it is probably higher than the full price, and paying full price means your price won't increase and hedges against future scale. it will also help pay for future development, which will benefit you


### if my business makes a product that builds on your software (the upstream), what will it cost ?
you don't need to pay anything during development. your end users will have the same responsibilities they would have if they used the upstream directly, so they'll need a use-license. if you release your software under either an OSI approved open source license or this license (and provide the source code), and don't charge for it, then you don't need to worry about this, other than to inform the user of their responsibilities. if you charge users for your software, then you must acquire on their behalf a (or verify that they have an existing) use-license from the upstream. otherwise, you must provide a list of known users to the upstream

if you wish to hedge against price increases, you may wish to purchase a number of full price use-licenses, which you can then resell. either way, you and your customers are protected by the strike price


### if i buy a version today, how does this license protect against price increases of future versions ?
a full price license entitles you to use any version released in the next year, so short term this offers some protection
also, much like FOSS, 3rd parties can develop similar functionality as those future versions based on the current version and compete with the upstream. this competition should help limit the price increases to real value added in future versions

a full price lifetime use-license can be upgraded to a later version. the greater of the price you paid and the current price will be credited towards the full price for the new version. similarly, for a per-annum license (with a locked in price), you can apply the maximum of the current full price and the price paid towards upgrading to a later version (full price)


### doesn't this license encourage you to make your software inefficient so it uses more cores
again, much like FOSS, 3rd parties can develop (and profit from) more efficient implementations and compete with the upstream. this competition should result in efficient implementations

if you have a use-license from upstream for a version, you can switch to a 3rd party (or your own) derivative at no additional cost (note: the 3rd party may charge for their version)


### can you give an example of an upgrade scenario
in 2016 you pay $10 each for full price per-annum use-licenses. in 2018, that price increases to $50 and a new version is released with a price of $80. you upgrade to the new version and pay $40 each - $10 for your lock-in price, plus $30 for the difference between the old and new version


### can you give an example of scaling my usage
in 2016 the prices are $0/$10/$100/$100 and you pay $10 each for 100 cores, locking in that price. in 2017 you pay $1000 to renew those licenses. in 2018 your company grows and you need 200 cores, but the prices have increased to $50/$50/$200/$100. you've had no lapses, so you're able to purchase the additional cores at $10 (your lock-in price) per-annum. if you'd used the sale price (paying $0 in 2016 and 2017), you'd have to pay $50 per core in 2018

note: this is an extreme example and i don't expect to increase prices this quickly


### why not just use a fixed price ?
initially, the ecosystem for this software is limited and early adopters are taking risk. the non-fixed price allows me to offer the software at a price that reflects the current utility and risk without limiting my ability to charge a higher price (more reflective of the total investment) later as the utility increases and the risk decreases. it also rewards early adopters


### why are non-production usages free ?
it's an arbitrary line, but:
- using the software to prototype new projects, learn how to use it, teach it to others, benchmark it, and test it helps adoption
- non-production uses don't necessarily indicate utility
- an organization using the software in production, and wishing to stop using it, might need to run extra instances of it to develop or test compatible systems. being able to reverse engineer the software is an important freedom and limits the negative effects of lockin

there's no perfect answer on where to draw the line, but this is a decent compromise


### are there any known flaws with this license
note: this refers to flaws in the license, not flaws in software that has been licensed with it
- IANAL
- i'd like to offer current users stronger protection, eg unlimited scale,
but can't figure out how to do that without being effectively fixed-price


what are the goals of this license ?
 - provide end users and ISVs with known future costs
 - provide the developer with income
 - encourage development of useable software, vs tools that will drive support-based income



#### copyright nqzero 2016