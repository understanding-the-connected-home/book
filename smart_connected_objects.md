# Connected things

## WRITTEN by peter
## PROOFED?

## Characteristics of a connected object

Depending on the field, the terms *smart* and *connected* are used largely interchangeably. For the purposes of this book, we'll primarily use the term *connected*. 

A connected object is one that:

- senses (i.e. takes input from the environment or a user) 
- thinks (i.e. computes and analyzes, often on the cloud)
- and then acts (i.e. makes something happen)

A connected object has a physical component. It can interact with the physical world either through its input or output, or both. A connected object is likely networked to other connected objects or digital services via the internet or local networks. 

### Sensing

Any way an object gathers information about its environment can be considered sensing. Other words to describe this, based on the overall context of the conversation, include tracking, surveilling, measuring (behavior, environmental data, etc.). 

### Thinking

Thinking, computing, data analysis or data processing is the process of analyzing and making sense of the input gathered previously. Input can include everything that was sensed, but also data sent through the network, or input given from a user.

### Acting

Based on sensing and thinking, the object or system acts: It performs some kind of output: Switching off a light, turning down the temperature, unlocking a door, sending a notification to a phone. These actions can be physical or digital, visible or invisible.

Often, but not necessarily, these three behaviours (sensing, thinking, acting) happen in chronological order. Just as likely they happen simultaneously, in parallel, or in ongoing loops. Especially when hooked into larger systems that work in unison these interactions can be quite complex; the basic model stands, though.


## Categories of connected things

The home is full of things that fall into various categories: furniture, lamps, appliances, gadgets, etc. For the connected home, we might need to re-examine these categories. 

Which categorization scheme might lead us to interesting insights? Let's explore a few.

### Connected v unconnected

The bluntest and most obvious categories. Binary, on/off. If we look at the last 10 years, this held up nicely: Table off, lamp off, phone on.

Over the last few years, the lines have started to blur: TV on or off? Fridge? Lamp? As more things come online, the distinction will become more or less meaningless - it might just be the default that changes.

### Active v passive data gathering and processing

Which devices, which things, in our home actively listen, sense, interpret, process, act on what's going on in the room? Which ones just sit there until we deliberately trigger them? Will we be able to distinguish these modes at all?

There are examples that are easy to match into categories, but often the lines can be blurry. 

For example, an Amazon Echo listens actively for commands; so does your Android phone if you set it up to react to the trigger word "OK Google". Yet, this processing of the trigger word is, to a large degree, processed locally. Once triggered, the devices fires up a connection to a server farm and gets ready. But how do we consider a hybrid active/passive filter like a geofence that triggers an action once we approach, say, our home with our phone? That system doesn't *listen* for audio cues, but it does track our behavior and switches from *kind of* passive to fully active. What about a motion sensor that is connected to the internet? What about a learning algorithm that doesn't act in a visible way at all but learns about and adapts to our behaviors?


## User acceptance

User acceptance varies wildly between different types of sensors in the home environment. For example, carbon monoxide detectors might be perceived as perfectly harmless whereas a microphone or camera is usually considered an invasion of privacy - or at least traditionally has been, even though this might be about to change.

While it isn't hugely surprising that a microphone that constantly listens to your every word would be perceived as more invasive than, say, an air quality monitor it's worth noting that even through consciously most people might reject the idea of having a microphone listening in on them, there are plenty of exceptions already. Trojan horses, if you will, that already have established themselves in our living rooms despite their (often active) microphones: Smartphones, laptops, game consoles, TVs. 

It looks like the list of actively listening things is about to take a sharp upturn through systems like personal assistants (Amazon Echo, Google Home), or voice controlled appliances like ovens. If it's voice-controllable, it's likely to include at least some level of active listening.

How user acceptance of these services will develop we don't know yet as the number of available systems is still small, the perceived value of the systems not yet as clear. Device makers certainly are making a big bet that consumers will flock to smart home hubs and other voice-controlled appliances. Just about every major tech company or home appliance manufacturer has some sort of smart play in the market.

How much so? At CES 2016, Samsung president BK Yoon announced that all Samsung televisions will be IoT devices by 2017, and within five years all Samsung hardware will be IoT-ready.[^1] This is not outrageous or even surprising - adding computation and network capabilities to consumer and home devices is getting so cheap it hardly makes sense to leave it out if even just a marginal improvement of the product is to be expected.


## Special categories (for now)

Some types of things seem to warrant their own categories as they might turn out to be special cases, at least for now.

First, **routers,** which might turn out to be the hub that controls all our smart home infrastructure. It's not clear this is how it's going to play out, but it's a strong scenario. Google's wifi router [On Hub](https://on.google.com/hub/) comes with all the protocols equipped, plus microphones and speakers. On the other hand, they also have a dedicated smart home hub in hte market (Google Home). Routers are already at the core of home connectivity, but also notoriously tricky to configure and maintain: They might just be the least beloved of all tech objects in anyone's home.

Second, **white goods** - dishwashers, fridges, washing machines, ovens - have been the connected fever dream of manufactures for years. ([The internet-connected fridge has become a running joke by itself.](http://fuckyeahinternetfridge.tumblr.com/)) There might be something there. Assume for a second that a scenario where we have a home server in every house; a local cloud solution of sorts. It's a long shot, but the fridge might not be the worst place to house this device, or to double as a hub if integrated smartly. 

We believe it's more likely that appliances will end up with minimum connectivity but with voice-controls: A hands-free scenario is useful for cooking whereas a fridge automatically ordering groceries seems somewhat invasive. This is purely hypothetical - we have at this point no data on user acceptance. All it takes to change the perception of a service or product is one product to get it just right: An iPhone moment for connected appliances that will not be an evolutionary, but a revolutionary step in that it doesn't just improve an oven to a slightly better oven but redraws the meaning and boundaries of the category entirely.

Third, **infrastructure**. What happens when existing infrastructure gets connected? Water pipes, heating, and the like? We see first steps with smart meters that measure electricity consumption and make it more transparent and actionable. There's still lots of previously dumb infrastructure to explore.

But also, what about the parts of a home we usually don't associate with anything worth connecting or likely to be connected? Floor boards, wall paper, blinds? It seems to early to tell.

Fourth, **truly new stuff**. The unknown unknowns we can only speculate about today but that will inevitably emerge - and likely sooner rather than later. This is the category that's both most speculative and most exciting; it's also the one to most likely cause major friction. We'll be watching with interest over the next five to twenty-five years.

[^1] See AV Interaction (Jan 2016): [http://www.avinteractive.com/news/samsung-announces-plans-to-make-all-tvs-iot-devices-by-2017-06-01-2016/](http://www.avinteractive.com/news/samsung-announces-plans-to-make-all-tvs-iot-devices-by-2017-06-01-2016/)
