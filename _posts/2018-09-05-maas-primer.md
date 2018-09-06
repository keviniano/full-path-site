---
title:        "A MaaS Primer for Community Transit"
description:  A primer for mobility as a service for those in community transit
excerpt:      A primer for mobility as a service for those in community transit
author:       Kevin Chambers
date:         2018-09-05
published:    true
header:
  image:      /assets/images/maas_primer_hero.jpg
---
_This is the second installment in a planned series presenting Full Path's perspective on community transit and technology. You can find the first one [here]({{ site.baseurl }}{% post_url 2018-08-01-hello-world %})._

This article is intended to summarize mobility as a service (MaaS) to the reader who has a background in community transit and hasn't yet had a chance to fully get their arms around this new jargon term and its technical implications.[^1] As with many terms coined to describe new and evolving concepts, it can be challenging to pin down what we're talking about. To achieve a level of brevity, I'll describe the industry consensus as I've seen it, tinged by my opinions on what MaaS _ought_ to be from a community welfare standpoint, independent of any particular company's business model. I'll wrap up by bringing it back to community transit and hitting the high points of what the sector's responses to this emerging trend can be.

[^1]: Also known as [Transportation as a Service](https://medium.com/reflections-by-ngp/the-road-to-transportation-as-a-service-b72c3fe780ec "An example article using the term TaaS"). Closely related are [Mobility on Demand](https://www.transit.dot.gov/research-innovation/mobility-demand-mod-sandbox-program.html "FTA prefers the term Mobility on Demand") and [Shared Use Mobility](http://sharedusemobilitycenter.org/ "The Shared Use Mobility Center — A leading supporter of MaaS in the United States"). As of this writing there appears to be no consensus on whether MaaS is pronounced like "mass" or "mahss".

## MaaS Defined
Mobility as a Service is where a technology platform brings together a collection of transportation options under one umbrella. The platform seeks to provide a spectrum of services that is so complete and a user experience that is so smooth that it can conveniently cover virtually every personal transportation need and can effectively replace personal vehicle ownership.

The "as a Service" suffix comes from the tech sector. It gained prominence with [software as a service](https://en.wikipedia.org/wiki/Software_as_a_service) (SaaS, pronounced "sass") and has since expanded to [many more areas](https://en.wikipedia.org/wiki/As_a_service). It reflects the broad trend where businesses reduce their in-house ownership and management of all manner of technology and instead contract with vendors on a subscription basis.

## For the User
The primary point of interaction with a MaaS platform for the user is through a mobile device app. A comprehensive MaaS solution addresses user needs with the following key capacities:
* **Easy Discovery**: The user can readily see from their smartphone all the relevant options for a given travel need.
* **Easy Decision-Making**: All the factors that affect the selection of the user's final option, such as cost and travel time, are presented in a clear and transparent fashion.
* **Easy Access**: For those modes that require booking, the booking process should be as seamless as possible. For options such as fixed route transit that don't involve booking, the system makes access easier with tools such as walking directions and real-time arrival information.
* **Easy Transfers**: In addition to providing the sorts of access features just described at transfer points, the platform can also respond proactively when delays or other events occur which require an updated itinerary.
* **Easy Payment**: Currently this can take a couple of principal forms. In one, the platform manages payment on a per-trip basis across services through a single "mobility wallet". In the other, the user subscribes to a mobility package which has a set monthly cost and grants the subscriber a defined level of access to a suite of services. Additionally, platforms can streamline the sharing of the costs of travel with third parties in much the same way some employers currently provide bus passes or merchants validate parking. Payment being a particularly intense area of innovation, this only scratches the surface of the models under development. Regardless, the expectation underlying all forms is that the rider's burden to deal with the minutiae of paying each service is reduced in some fashion.

## Under the Hood
MaaS relies on some infrastructure above and beyond the obvious mobile device app:
* **Density**: At present the cost of building out a MaaS platform pencils out only in urban spaces, where population density can support a wide range of mobility services and the costs of maintaining the platform itself can be spread across many users. Expect platforms to gradually expand into outer suburbs and smaller towns as the systems and approaches to implementation mature.
* **Transit**: Mass transit is uniquely suited to scale to the longer distance people-moving needs of dense urban spaces, so it sits squarely in the center of any MaaS ecosystem that hopes to broadly replace the personally owned vehicle. Bike-share, e-scooters, ride-hailing, ride-sharing, and car-sharing will be vital to supplying short-distance trips and first/last mile gaps, but they cannot replace the backbone of the system.[^4] Above and beyond its raw capacity and space efficiency, as public infrastructure mass transit is accountable for and has the infrastructure to respond to community expectations with regard to equity, inclusion, and environmental impacts. It can help assure that a MaaS platform serves the entire community.
* **Markets**: Another way to define mobility as a service is as a _low-friction mobility marketplace_. Clichés about invisible hands aside, the matter of how to develop a functional specialized market is not trivial. Significant effort must be invested in establishing one in a way that builds in the transparency and basic sense of fairness to generate trust from everyone involved. Expect one area of controversy about how MaaS markets will work to center on publicly accountable "open" markets versus privately controlled "walled garden" approaches.
* **Policy**: If only because of their reliance on transit and the public right-of-way, MaaS implementations will inevitably involve public-private partnerships of one sort or another. Thoughtful public policy will be critical to assuring the success of those partnerships and the markets they seek to foster. Policymakers will play a critical role in setting the incentives that drive the MaaS marketplace's outcomes. In addition, myriad laws and regulatory frameworks which currently favor car ownership will need to be reevaluated, from the immensity of regional [congestion pricing](https://en.wikipedia.org/wiki/Congestion_pricing) to the minutiea of [curb access](http://www.fehrandpeers.com/curbside-management/).
* **Open Data**: Do an [image search](https://www.google.com/search?q=maas+mobility+as+a+service&tbm=isch "Google image search for MaaS") for mobility as a service and you'll be presented with one diagram after another with lots of icons that represent the variety of services available to the consumer, connected together with lots of lines. All those lines — they rely on open data. Whether it's actual public data such as transit schedules[^7], the standardized formats[^8] they're put into, or the application programming interfaces (APIs)[^5] that allow for the easy exchange of that formatted data between systems, open data is critical to allowing otherwise independent services to participate in a larger ecosystem.
* **A Hub**: This is the definitional ingredient that seems to get lost sometimes amid all the talk about [TNCs](https://en.wikipedia.org/wiki/Transportation_network_company) and the development of new modes like electric scooters. There must be at least one entity that coordinates the transportation services in the network, brokers payment between the customer and the provider, and manages the marketplace as a whole.[^9] Failing this element, mobility is not being presented as a single service, and we're back to the consumer managing their relationship with each of their options one by one. Who operates the hub, how it generates revenue, how it protects user privacy, how it keeps the mobility marketplace fair and transparent, and how to measure its progress toward achieving community goals — all are important topics that will drive the success or failure of the system as a whole.

[^4]: Here are a [couple](https://humantransit.org/2016/08/pushing-back-on-ridesourcing-and-microtransit-pr-the-video.html) [illustrations](https://twitter.com/CyclingSurgeon/status/808070108895735809) help demonstrate the limitations that cars — even shared or autonomous cars — have in the urban context.

[^7]: See for example [TransitFeeds](https://transitfeeds.com), repository of fixed route transit services.

[^8]: One of the oldest and most widely used standards that a MaaS system would rely on is the [General Transit Feed Specification](http://gtfs.org). It's currently used by Google, Apple, and many others for providing transit directions. Another is the [General Bikeshare Feed Specification](https://github.com/NABSA/gbfs). More are needed. A good roundup of the current state of affairs can be found [here](https://trilliumtransit.com/2017/12/31/data-formats-roundup-2017/).

[^5]: It's hard to understate the importance of [APIs](https://en.wikipedia.org/wiki/Application_programming_interface) to participation in a network of mobility services, because they're what give your services real-time visibility to apps — your own or someone else's. See [TriMet](https://trimet.org) in Portland, Oregon for one example of a transit agency that has APIs it [shares](https://developer.trimet.org/ws_docs/ "The applications programming interfaces for TriMet, the transit agency in Portland Oregon") with app developers.

[^9]: By this definition, a platform must include all four levels described in the [MaaS topology](http://www.tut.fi/verne/aineisto/ICoMaaS_Proceedings_S6.pdf) developed by Jana Sochor, et al.

## Nice-To-Haves
There are a number of other things that are associated with MaaS, due either to their coexistence in the realm of transportation innovation, or because of their hotness in the technology field. These include:
* Microtransit[^2]
* Electric vehicles
* Autonomous vehicles
* Blockchain[^6]

[^2]: Like MaaS, microtransit is another loosely defined term, prone to hype. I'll leave that to another article. While a promising tool in some scenarios to extend transit coverage, it's not a must-have.

[^6]: Here is [one](https://medium.com/iomob/mobility-as-a-service-maas-and-mobility-on-demand-mod-via-blockchain-64e36a2f6676) of many ideas out there for bringing blockchain technology to MaaS.

All of these are possible contributors to the success of a MaaS ecosystem, but none of them are requirements. In other words, we don't need to wait for any of these to further mature before getting started on building out MaaS in our communities.

## The End Game
Advocates for mobility as a service hope that fully deploying it in a form that is cost-competitive with the personally owned automobile will result in "[peak car](https://www.bloomberg.com/news/articles/2018-08-17/-peak-car-and-the-end-of-an-industry "Bloomberg article about peak car")". Widespread reduction in car ownership could bring myriad social and environmental benefits: congestion reduction, accelerated decarbonization of the transportation sector, fewer vehicle-related fatalities, and reuse of urban space which is currently dedicated to parking, to name just a few. With transportation now the [leading source](https://rhg.com/research/preliminary-2017-us-emissions/) of carbon emissions in the US, MaaS presents an opportunity that can be seized now to significantly reduce the role personal mobility plays in climate change.

## Following the Money
Large investors appear to be making strategic and long term investments based on anticipation of a major shift in how personal mobility is achieved. While there are few fully integrated MaaS platforms in operation, indeed none yet launched in the US, large investments are being made in the component services. Hardly a week goes by without a large player in the transportation field announcing a major investment, initiative or acquisition to better position itself for an expanding MaaS sector.
* McKinsey [reported](https://www.mckinsey.com/industries/automotive-and-assembly/our-insights/analyzing-start-up-and-investment-trends-in-the-mobility-ecosystem) that "sharing solutions" have received more investment ($36.5B) than any other category of mobility startup from 2010 to 2017. They anticipate [disruptive growth in shared mobility](https://www.mckinsey.com/industries/automotive-and-assembly/our-insights/the-automotive-revolution-is-speeding-up) from less than one percent market share of automotive revenue in 2016 to 20 percent in 2030.
* Most major car manufacturers have launched some sort of car sharing service, such as [Car2Go](https://www.car2go.com) (Daimler), [ReachNow](https://reachnow.com) (BMW), [Maven](https://www.maven.com) (GM), [Hui](https://www.drivehui.com) (Toyota), and [Ford Carsharing](https://www.ford-carsharing.de). [Others](https://www.engadget.com/2018/07/05/vw-and-renault-electric-car-sharing-services/ "VW and Renault plan car sharing services") are [planning](https://www.livemint.com/Auto/tIQQue2wXPWL6TMVSEvNxM/Hyundai-partners-Revv-to-enter-car-sharing-space-in-India.html "Hyundai has plans for a car sharing service in India") to do so.
* In April of this year Uber [acquired](https://www.theverge.com/2018/4/9/17213994/uber-acquires-dockless-bike-share-jump) [Jump](https://jumpbikes.com/), a major manufacturer for and now operator of bike-share systems, indicating a commitment to extending its reach beyond car-based modes.
* Lyft, seemingly in response, moved to [acquire](https://www.theverge.com/2018/7/2/17526892/lyft-buys-motivate-bike-sharing-expansion) [Motivate](https://www.motivateco.com/), a major operator of bikeshare systems, shortly thereafter.
* E-scooter companies have collectively raised over a [billion dollars](https://techcrunch.com/2018/06/29/electric-scooter-startup-spin-is-finalizing-a-125-million-security-token-offering-on-the-blockchain/) in venture capital, noteworthy for a mode that scarcely existed a year ago. Uber is a [backer](https://www.theverge.com/2018/7/9/17548848/uber-investment-lime-scooter-alphabet) of [Lime](https://www.li.me) and will be making Lime's scooters available to rent in the Uber app.

## How Can Community Transit Respond?
Some broad categories of ways to engage with this new approach to mobility:

### Advocate
We're only talking about using technology to dramatically shift how people get around. What could possibly go wrong?

A lot, of course. At least in some of their [materials](https://www.youtube.com/watch?v=KTQLulPUowE "MaaS video by Deloitte"), promoters of MaaS focus on the convenience and gee-whiz technology that cater particularly to commuters with disposable income. Those of us familiar with the lives of people with barriers to transportation know that including their needs in regional plans doesn't just happen. It's the result of intention by dedicated individuals and, sometimes, hard-fought battles.

If you are in the orbit of a large urban area, you can assume that conversations about how to implement MaaS are happening today in your area at some level of government. I encourage you to find out who's doing that now in your city, region, county, state or province. Get on their mailing list and see to it that the interests of folks you serve are represented on their working groups. Community transportation providers and those they serve are well positioned to advocate for policies that prevent the expansion of the [digital divide](https://en.wikipedia.org/wiki/Digital_divide) into mobility. No technology need be purchased for this response.

### Participate
Many community transit services are already designed to fill a coverage gap for the general public that mass transit cannot. These are just the ones that would fit perfectly into a MaaS ecosystem, perhaps after some strategic technology upgrades. Agencies providing these services should have MaaS on their radar now and start developing plans for how they can engage with a platform, be it through publishing real-time ETAs, supporting automated booking by 3rd parties, or planning other integrations.

### Expand
As momentum grows for communities to reduce their reliance on personally-owned vehicles, so will the opportunities for existing players with on-the-ground expertise in running specialized operations. A fully realized MaaS ecosystem is going to have a lot of niche roles that will need to be filled. Community transit providers, ever the experts in niches, stand to gain if prepared for change.

### Emulate
I propose that the tenets of mobility as a service rise to be the central organizing principles guiding technology strategies across the community transit sector. In those areas where a full-blown MaaS ecosystem is not yet viable, there are still evolving public expectations to contend with, largely driven by the rapidly changing technology landscape. Even if you're the only show in town, easy discovery, access, transfers, and payment are universal elements of good customer service for any mobility operation.[^3] Those agencies that make a strategic preference for technologies that move away from monolithic architectures and embrace open data will be far more prepared when some version of MaaS comes knocking.

[^3]: In truth, no community transit provider is an ever an island, even in the most rural area. Rather, each is a bridge and a lifeline, so there are always opportunities to explore for coordination with the resources being linked: medical providers, social services, volunteer drivers, etc.

### Retrench
Expect there to be cases where a given service can be better and more economically provided by a for-profit venture armed with the technology resources to fully participate in a MaaS marketplace.[^10] While this may lead to a some agencies shutting down entirely, I suspect that will be the minority case. For most organizations, it will be an opportunity to refocus to the next "tough nut to crack" that addresses a key community need.

[^10]: This is not to sanction current pricing by TNCs, which is designed to gain market share and is not sustainable from either [corporate bottom line](https://www.reuters.com/article/uber-results/uber-narrows-loss-but-still-a-long-way-from-profitability-idUSL1N1V611I) or [driver compensation](https://www.washingtonpost.com/news/the-switch/wp/2016/06/27/how-much-uber-drivers-actually-make-per-hour/?utm_term=.4f106b854396) standpoints. Rather, displacement of community transit providers (that won't be regretted later) will be the result of the development of sustainable business models and technologies that directly address the barriers preventing portions of the population from accessing transportation while considering and supporting the community functions that transportation plays in people's lives.

In future articles, I'll take deeper dives into some of the aspects of transportation and technology I've touched on here and how they affect community transit.
