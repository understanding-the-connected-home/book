# Negotiating with connected systems

_As we invite more algorithmic agents into our lives, we'll see more conflicts both between machines and humans, as well as among machines. How can we understand and mediate these conflicts?_

## WRITTEN: M
## PROOFED?

How can interactions and understanding be mediated across the human-readable and machine-readable layers? 

Here we discuss the idea of a "user agent" that translates and negotiates across the layers. Historically, this has been metaphor-based software (GUIs) like the browser or mobile operating system. It might look different going forward. 

- As we invite more algorithmic agents into our lives, we'll see more clashes between them and, to a lesser degree, us.
- For now, humans will be the ones who have to mediate these conflicts. In the future, machines may take on more negotiation.
- Figuring this out is a clear challenge for interaction designers.


## Where conflicts arise

Whenever we enter or leave a connected environment, some type of data engagement will take place. Whether it is opt-in or opt-out or something more granular, whether it is an all-or-nothing, binary choice like a EULA, or something negotiated between humans or software agents. 

We need to find ways to make this type of interaction and exchange understandable, human-readable, and negotiable.

It seems better to discuss today how to get this right, or at least how to ask the right questions that will arise tomorrow.

The other aspect is the negotiating of agreements on a (semi-)automatic level. Even more than on the web, in the physical space we need to be in control of our privacy. 

For example, CCTV cameras in the public space are somewhat controversial because they do not reliably prevent crimes while increasing the level of surveillance; Wifi sniffing trash cans crossed the line.[^1] This is a case-by-case negotiation of what's acceptable in the public environment.

In homes—both permanent and temporary—stricter rules should apply. Privacy is key, and strong privacy protection must be the default. We need opt-in, not opt-out, for the sharing of personal information.

So what could that look like? What's the interface for negotiating these questions? What are the social norms going to be? What kind of recourse might there be for cases of abuse?

We cannot yet answer these questions but can make some educated guesses:

- **Social norms might solve many of these questions before they even become problematic.** Most home owners might turn down "sniffing" levels to the lowest default, while some early adopters turn it up. In both cases, their friends and peer group should self-select, exactly like it happens today. Some people use CCTV cameras on their premises, others don't. Some have guns in their homes, others don't. Some play loud music, others don't. No technological negotiations are at work here. Social interactions, legal regulation and cultural norms are used to resolve these things.
- **Design principles that honor privacy will win the market.** It makes sense to honor privacy in the home and to make it an overwhelmingly strong default. The market might simply solve this as users vote with their money. Different regions/markets might produce different outcomes, as these preferences differ across countries.
- **Smart contracts could provide a technological backend.** Unlike in software and web services where users are routinely forced to accept End User License Agreements (EULAs), there is a window of opportunity to create a better system for IoT in general and the connected home in particular. Each person could store their personal agreements on a digital ID that negotiates a deal with the connected environment. Say Alice the visitor is fine to be sniffed for wifi devices, refuses to be captured by CCTV, and doesn't have a strong preference around mood lighting. Bob the home owner has similarly expressed his preferences. A relatively simple algorithm could match them up so that the camera stops recording, while Bob's mood lighting preferences override Alice's (since she doesn't care anyway) and the system does connect to Alice's wifi devices because she agreed to it.[^2] For heightened security needs, the blockchain could be used to verify these negotiations. This might seem like overkill now, but might turn out to be relatively seamless and offer smooth sailing.
- **We need a Do Not Track for the physical space.** As a lowest-common denominator, we might need Do Not Track not just for connected homes, but especially for smart cities and connected retails spaces. This could be a device or service that allows us to reliably opt-out of marketing & advertising tracking as it enters physical spaces.

These rules and types of interactions need to be human and machine readable. For any of this to work, we need to come up with a way to communicate these rules in a format that is legible by humans and machines alike, like Creative Commons licenses.[^3] 

## Managing Conflict

When we introduce connectedness into infrastructure like buildings—into our homes—we stitch a technological network into our lives. And with it we introduce smart agents of sorts. Software that has more or less its own goals and agendas.

For example, a Nest thermostat's primary goal might be to achieve and maintain a certain temperature in the living room; a secondary goal might be to save energy.

The owner of the Nest has given that objective to the thermostat. And while it will undergo some interpretation at the hand of the algorithm (say you express you prefer a desire for the temperature to be 19° Celsius and the algorithm knows to translate this statement into "you want 19° Celsius in your living room _when you are at home_ but while you're gone temperature can vary to lower energy consumption"), the goals come more or less from the user.

The user this example is a _single human being_. It's important to stress this as these kinds of interaction models tend to break down, or at least be challenged, along three axes once we do not talk about single-user scenarios:

- user-to-user conflicts
- user-to-agent conflicts
- agent-to-agent conflicts

### User-to-user conflicts 

In a multi-person household, the technology could easily be faced by conflicting goals. Think a couple with different temperature preferences. These are things that technology won't be able to solve elegantly. They are social challenges that require social solutions, not technological ones.

### User-to-agent conflicts

If the multi-user scenario challenge wasn't hard enough, think of example of friends mentioned recently, in which only one partner uses the thermostat's app and the other doesn't want to engage with it. In the latter case, thermostat doesn't recognize that person as a user. 

If the app user isn't at home, but the non-app user is, the thermostat reads the home as empty. It doesn't turn on by itself but requires human intervention. 

This is clearly a technological problem, and one that should have never appeared to begin with. Technology, especially in the home, needs to be sensible about its demands on the residents.

### Agent-to-agent conflicts

When we introduce smart appliances to our home, we deal with software agents. Individually, in isolation, these might do a good, or good enough, or even stellar job. But combined into a complex and often unpredictable network, it can all get a little messy. Here we need a systemic view. This is seriously challenging terrain for designers.

Good friend and excellent systems thinker/designer Louisa Heinrich articulated this perfectly with an example of different appliances fighting over the blinds being open or closed based on their respective goals: The coffee machine wants them closed so the milk keeps longer, dishwasher wants them open to grab some solar power, the Nest wants them closed to keep the temperature low, the plants want them open... 

Who moderates these conflicts? What happens when you—the master—are not at home?[^4] 

In Louisa's words, "There is a narrow but very deep gap between assistance and replacement."[^5]

## When things clash

We still need a bit of a framework to interrogate and explore these conflicts between the smart agents in our environment. 

Enter Scott Smith, who at ThingsCon 2015 shared his excellent research project, Thingclash. It's a framework for considering cross-impacts and implications of colliding technologies, systems, cultures and values around the IoT:[^6]

[![Scott Smith at ThingsCon](https://raw.githubusercontent.com/understanding-the-connected-home/book/master/img/talk_scottsmith.png)](https://www.youtube.com/embed/CjcJfGrWKNA)

As Scott points out starting around the 27 min mark (but we strongly recommend watching the whole talk), it's crucial to think about the legacy of UX decisions, business models, etc., to explore the different cross-impacts, the implications.

> "Can we find a way to surface and make legible the tensions and the frictions and the conflicts that arise when new connected, data-collecting objects are introduced into our world?"

For now, just assume that putting several smart agents/appliances to work side by side might yield unintended consequences. These might not be devastating—most likely they're simply annoying, like lots of notifications on your phone or shutters that open and close seemingly at random. But as more things are connected, the clashes could become more dire. 

## Who is the user agent? 

The question now is that if you fill an environment with humans and connected objects, is there something that helps the humans navigate everything and to facilitate between humans and machines?

We'd argue there is a need for a tool of interpretation that can advocate on the user's behalf. This might be software or some device that that articulates the users' interests, ensures they are respected by the machines in the environment, and also communicates back what the machines are saying and doing. 

This tool could function like the web browser does today when surfing online. As a user moves through connected environments, the brower helps interpret or render that environment for the user. It is also a protective program, sometimes taking action on the user's behalf, such as blocking malware or spam. 

This interpretation tool can also communicate preferences to devices and connected environment. It might also be where conflicts among devices and preferences are brought to the attention of the user, who can parse and override certain decisions. This could also be the interface for the user to express themselves, either to machines in the environment or to other users.

Given the above needs, the smartphone may be a natural place to start exploring what a user agent in the connected home could look like. 

[^1]: Wifi sniffing smart rubbish bins installed, and then abandoned, in London a few years ago. [cnet.com/news/london-tosses-out-wi-fi-sniffing-smart-bins](http://www.cnet.com/news/london-tosses-out-wi-fi-sniffing-smart-bins/)
[^2]: Read more about what smart contracts could look like in practice in our [Controlling Privacy chapter.](controlling_privacy.md)
[^3]: Read more about human-readable and machine-readable layers in our [Interaction layers chapter.](interations.md)
[^4]: Watch Louisa Heinrich's talk at NEXT14, especially around the 7 minute mark: [video.nextconf.eu/v.ihtml?photo%5fid=9802229](http://video.nextconf.eu/v.ihtml?photo%5fid=9802229). 
[^5]: See [louisaheinrich.com/2015/03/23/good-help-is-hard-to-find-post-26100](http://www.louisaheinrich.com/2015/03/23/good-help-is-hard-to-find-post-26100/) 
[^6]: Check out Scott Smith's research project [thingclash.com](http://www.thingclash.com/) and his personal website [changeist.com](http://changeist.com).

