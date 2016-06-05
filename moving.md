# Moving in and out of homes

_If we live inside a computer, how do we handle and maintain our data? How does data change the way we live in a house or move in and out?_

A connected home is a home kitted out with sensors and network infrastructure—it is essentially a computer we live in. 

That means we need to consider implications of security and control.[^1] It also means we need to think about technical failure and personal data.

Most failure situations in a connected home are likely to be variations of: 

* Users not understanding their home's infrastructure[^2]
* Things clashing with things[^3]

Designing interactions to mitigate these issues and building them in a way that is reliable and user-readable (read: fixable) will be key. You don't want your flat's operating system to crash on you.

## Computers crash

Not understanding your home (or not being understood by it) is bad enough. But what happens in case of a more fundamental crash? What does the blue screen of death look like for a home?

![blue screen of death](https://upload.wikimedia.org/wikipedia/commons/3/3b/Windows_9X_BSOD.png)

_The blue screen of death, universal symbol of crashed computer systems.[^4]_

Can you reboot your apartment? How? Have you tried turning it off and on again?

![Have you tried turning it off and on again?](https://media.giphy.com/media/F7yLXA5fJ5sLC/giphy.gif)

_The IT Crowd: Have you tried turning it off and on again?_

Often, a simple reboot of the wifi router or oven will do the trick. But what about more systemic cascading crashes? The more complex a networked system the more likely bugs and crashes are to domino. Currently we don't have the infrastructure—or help hotline—to help us fix these issues.


## Moving in & out

We don't know yet what kind of data will be common to be created in the apartment and moved with us from one place to another. But we do know that moving with both data and preference settings will be "a thing" we all do.

As a way of exploring mechanism that might help us with this process (independently from the types of data), we created a bit of speculative design for The Good Home[^5]: the Home Totem[^6]:

> The Home Totem represents the owner’s privacy and sharing preferences. It also serves as a link between the home and the owner’s secure data or profile on the internet. Think dietary requirements, energy consumption profiles, records of former home ownership and the like.

> The Home Totem is a physical avatar that the owner moves from home to home. When they move in, they set down the Home Totem and the home adjusts its privacy and sharing preferences accordingly. By moving it from one connected home to another they transfer their preferences to the new home and establish residency. In a sense, it is the heart of the connected home as far as the residents are concerned.

![Good Home: Home Totem](http://i2.wp.com/thegoodhome.org/wp-content/uploads/2016/04/HomeTotem_sketch.png?w=640)

_The Home Totem is a piece of speculative design created by Peter Bihr for The Good Home Project._

The core idea is to make it easy to establish residency by simply putting down this symbolic object. It would hide the backend work of setting preferences, linking a digital ID to the place, etc. 

In the sketch you'll notice that the Home Totem consists of several pieces stacked on top of one another. This might be a blunt, but intuitive way to allow for moving in and out of shared living situations. 

### What happens when you move out of your home?

When stacked, shared residency and preference/data settings are in effect. Upon moving in or out, you would add or remove your piece from the stack, triggering a change of the settings.

As we fill our networked homes in personal data, as our kitchen clouds and algorithmic assistants learn about our behaviors and preferences, we imprint ourselves on our living spaces not just physically as we have done traditionally, but also digitally, through data.

And much like we tend to renovate and paint the walls either upon moving in or moving out (depending on which country you're in) we'll want to do the same on the data & algorithmic level.   In other words, what does it look like to reset the apartment? 

Just like we don't want to leave any smudges or holes on a wall after living at a place, we don't want to hand over a house with our data still inside it. *Fresh coat of paint, please.*

## Factory Reset

So how does a factory reset work? Does it wipe all data completely? Are there parts of our home's neural network that cannot be fully wiped, just like really old houses have grooves in their wooden floors from generations of people walking the same beeline from bedroom to bathroom? 

When we arrive in a new place, do we start from scratch or do we transfer everything over to the new place? (Think about the hassle it still is to move your data and settings to a new computer!)

What if the location change is only part of what's new? For example, what happens if a couple splits up, and their home's data sets were generated by two people, and now the new place is for one? Will data from a bachelor pad seep into a new shared couple's space, like some old Bob Marley poster? Will it be greeted by the other data set with a similar kind of resentment as its physical counterpart? When children grow up and leave the home, do they take their childhood data with them? Or does it get boxed up and stored as mementos, to be recalled and possibly discarded at a later date, while meanwhile clogging up their parents' basement?


## Maintenance and logging

As another contribution to The Good Home project, Alexandra Deschamps-Sonsino created the Home Sweet[^7]:

> When we think of the home in the UK, we’re talking about a living and breathing infrastructure which moves and reacts to its environment. I’ve lived in homes that have leaked, had to replace boilers, flooring, tiles, grout. It’s always felt like an endless battle, and many moves in London have added to the feeling of unsteadiness. Every time I move, I ask the same questions: the landlord’s details, where the meters are, how to turn on the taps without burning myself. I get insurance policies moved over, making a set of assumptions on information I don’t have yet: when the building was built, whether there has been subsidence recently. I bring in my own data but I also need a lot of information that belongs to the home itself.

> Home Sweet is a sketch of a digital service that captures and hosts a home’s data forever (presumably set up by the local council) enabling owners and tenants to come and go with their own data but also leave something behind for the next person.

![Good Home: Home Sweet](http://i0.wp.com/thegoodhome.org/wp-content/uploads/2016/04/SweetHome_sketch.png?w=640)

There is potentially great value to be gained by logging and unlocking this type of data and building services around is.

Think about just how much easier it makes the life of residents to be able to tap into this kind of maintenance log, find out who has in the past provided reliable maintenance and repair services (or botched them up), to see if there are bits and pieces of infrastructure that have been creating problems over and over.

When buying a home, this type of data is notoriously hard to find or verify, yet priceless. The documentation on infrastructure in homes (especially older ones) is usually thin and bad. This holds especially true in cities where there is a higher turnover of residents.

There is tremendous potential in figuring out how we handle data residue when moving in and out, and how to unlock services built on top of this type of data. This goes for the individual unit as much as for the neighborhood or city-wide level.

How do we merge our individual sets of "home data" when moving together, and divide it up upon moving out?

What do failure modes in connected homes look like? Is there an off switch? How can we build and design connected homes to be resilient and if they fail to do so gracefully?


[^1]: As Cory Doctorow does here: [wired.co.uk/magazine/archive/2015/07/features/stop-spies](http://www.wired.co.uk/magazine/archive/2015/07/features/stop-spies)
[^2]: See the chapter [Future](future.md) or for earlier thoughts on this topic: [thewavingcat.com/2015/08/03/understanding-the-connected-home-ground-rules/](http://www.thewavingcat.com/2015/08/03/understanding-the-connected-home-ground-rules/)
[^3]: See the chapter on [Negotiating](negotiating.md), or for earlier thoughts [http://www.thewavingcat.com/2015/08/17/understanding-the-connected-home-managing-conflict/](http://www.thewavingcat.com/2015/08/17/understanding-the-connected-home-managing-conflict/)
[^4]: Source: Wikipedia [commons.wikimedia.org/wiki/File:Windows_9X_BSOD.png#/media/File:Windows_9X_BSOD.png](https://commons.wikimedia.org/wiki/File:Windows_9X_BSOD.png#/media/File:Windows_9X_BSOD.png), Licensed under Public Domain via Wikimedia Commons.
[^5]: More about the Good Home project and the other exhibits we made for the Fuori Salone at Milan see [thegoodhome.org/projects](http://thegoodhome.org/projects/)
[^6]: See [thegoodhome.org/projects/home-totem/](http://thegoodhome.org/projects/home-totem/)
[^7]: For a more detailed presentation see [thegoodhome.org/projects/home-sweet/](http://thegoodhome.org/projects/home-sweet/)
