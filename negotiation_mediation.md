# Negotiation and Mediation

## WRITTEN?
## PROOFED?

How can interactions and understanding be mediated across the human-readable and machine-readable layers? Here we discuss the idea of a "user agent" that translates and negotiates across the layers. Historically, this has been metaphor-based software (GUIs) like the browser or mobile operating system. It might look different going forward. 

- As we invite more algorithmic agents into our lives, we'll see more clashes between them and, to a lesser degree, us.
- For now, we will be the ones who have to mediate these conflicts: Hopefully this won't last long.
- Figuring this out is a clear challenge for interaction designers.


## Negotiation

**Whenever we enter or leave a connected environment, some type of data engagement will take place.** Whether it is opt-in or opt-out or something more granular, whether it is an all-or-nothing, binary choice like a EULA, or something negotiated between humans or software agents: **We need to find ways to make this type of interaction and exchange understandable, human- and machine-readable, and negotiable.**

It seems better to discuss today how to get this right, or at least how to ask the right questions that will arise tomorrow.

The other aspect is the negotiating of agreements on a (semi-)automatic level. Even more than on the web, in the physical space we need to be in control of our privacy. 

CCTV cameras in the public space are *somewhat* controversial because they do not help prevent crimes but increase the level of surveillance; wifi sniffing trash cans (like implemented, [then abandoned](http://www.cnet.com/news/london-tosses-out-wi-fi-sniffing-smart-bins/), in London a few years back), crossed the line. This is a case-by-case negotiation of what's acceptable in the public environment.

In homes - both permanent and temporary - tougher rules should apply. **Privacy is key, and strict privacy protection must be the default. We need opt-in, not opt-out, to the sharing of personal information.**

So what could that look like? What's the interface for negotiating these questions? What are the social norms going to be? What kind of recourse might there be for cases of abuse?

We cannot yet answer these questions but can make some educated guesses:

- **Social norms might solve many of these questions before they even become problematic.** Most home owners might turn down "sniffing" levels to the lowest default, while some early adopters turn it up; in both cases their friends and peer group would self-select, exactly like it happens today: Some people use CCTV cameras on their premises, others don't. Some have guns in their homes, others don't. Some play loud music, others don't. Not technological solution are at work here. Social self-selection, legal regulation and cultural norms are used to regulate these things.
- **Design principles that honor privacy will win the market.** It makes sense to honor privacy in the home and to make it an overwhelmingly strong default, and the market might simply solve this as users vote with their money. Different regions/markets might produce different outcomes.
- **Smart contracts could provide a technological backend.** Unlike in software and web services where users are routinely forced to accept (rationally often unacceptable) End User License Agreements (EULAs), there is a window of opportunity to create a better system for IoT in general and the connected home in particular. **Each person could store their personal agreements on a digital ID that negotiates a deal with the connected environment.** Say Alice the visitor is fine to be sniffed for wifi devices, refuses to be captured by CCTV, and doesn't have a strong preference around mood lighting. Bob the home owner has similarly expressed his preferences. A relatively simple algorithm could match them up so that the camera stops recording, Bob's mood lighting preferences overrule Alice's (since she doesn't care anyway) and the system does connected to Alice's wifi devices because she agreed. For heightened security needs the blockchain could be used to verify these negotiations. This might seem like overkill now, but might turn out to be relatively seamless and offer smooth sailing.
- **We need a Do Not Track for the physical space.** As a lowest-common denominator, we might need Do Not Track not just for connected homes, but especially for smart cities and connected retails spaces: A device of sorts that allows us to reliably opt out of marketing and advertising tracking.


**These rules and types of interactions need to be human and machine readable.** For any of this to work, we need to come up with a way to communicate these rules in a format that is legible by humans and machines alike (like [Creative Commons licenses](https://creativecommons.org/licenses/)). In other words, standardization for different types of data based interactions.

## Managing Conflict

When we introduce connectedness into infrastructure like buildings - into our homes - we stitch a technological network into, or better: onto, our lives. And with it we introduce smart agents of sorts: Software that has more or less its own goals and agendas.

For example, a Nest thermostat's primary goal might be to achieve and maintain a certain temperature in the living room; a secondary goal might be to save energy.

The owner of the Nest has given that objective to the thermostat. And while it will undergo some interpretation at the hand of the algorithm (say you express you prefer a desire for the temperature to be 19° Celsius and the algorithm knows to translate this statement into "you want 19° Celsius in your living room _when you are at home_ but while you're gone temperature can vary to lower energy consumption"), the goals come more or less from the user.

"User" as in _singular human individual_. It's important to stress this as these kinds of interaction models tend to break down, or at least be challenged, along three axes once we do not talk about single-user scenarios:

- user-to-user conflicts
- user-to-agent conflicts
- agent-to-agent conflicts

**1.) User-to-user conflicts:** 
In a multi-person household, the technology could easily be faced by conflicting goals. Think a couple with different temperature preferences. These are things that technology won't be able to solve elegantly: They are social challenges that require social solutions, not technological ones.

**2.) User-to-agent conflicts:** 
If the multi-user scenario challenge wasn't hard enough, think of the couple a friend mentioned recently, in which only one partner uses the thermostat's app and the other doesn't want to engage with it. In the latter case, thermostat doesn't recognize that person as a user. 

If the app user isn't at home, but the non-app user is, the thermostat reads the home as empty. Then it doesn't turn on. 

This is clearly a technological problem, and one that should have never appeared to begin with. Technology, especially in the home, needs to be sensible about its demands on the residents: No appliance should ever force a resident to engage with it in order to function properly.

**3.) Agent-to-agent conflicts:** 
When we introduce smart appliances to our home, we deal with software agents. Individually, in isolation, these might do a good, or good enough, or even stellar job. But combined into a complex and often unpredictable network, it can all get a little messy. Here we need a systemic view. This is seriously challenging terrain for designers.

A good friend and excellent systems thinker and designer Louisa Heinrich articulated this perfectly with her example of different appliances fighting over the blinds being open or closed based on their respective goals: The coffee machine wants them closed so the milk keeps longer, dishwasher wants them open to grab some solar power, the Nest wants them closed to keep the temperature low, the plants want them open... 

Who moderates these conflicts? What happens when you - the master - are not at home? Here's [Louisa Heinrich](http://louisaheinrich.com) at NEXT14 (esp. starting around the 7min mark):

[![Louisa Heinrich at NEXT](https://raw.githubusercontent.com/understanding-the-connected-home/book/master/img/talk_louisaheinrich.png)](http://video.nextconf.eu/v.ihtml?photo%5fid=9802229)

The underlying question here is, of course, if automation is really that desirable - it strikes us as a low-hanging fruit and only a small part of the potential upside, but one fraught with downside (see the [Framing The Debate post](http://www.thewavingcat.com/2015/08/07/understanding-the-connected-home-framing-the-debate/) from this very series for more).

Groundbreaking researcher and interface researcher Douglas Englebart framed it right (thanks to [Scott Jenson](http://jenson.org/) for the pointer!) in the motto:

> "[Augmentation not automation](http://www2.iath.virginia.edu/elab/hfl0035.html)". 

Or once more in [Louisa's words](http://www.louisaheinrich.com/2015/03/23/good-help-is-hard-to-find-post-26100/): "There is a narrow but very deep gap between assistance and replacement".

We still need a bit of a framework to interrogate and explore these conflicts between the smart agents in our environment. Enter [Scott Smith](http://changeist.com) at [ThingsCon](http://thingscon.com) earlier this year and his (most excellent) research project [Thingclash](http://www.thingclash.com/), a framework for considering cross-impacts and implications of colliding technologies, systems, cultures and values around the IoT:

[![Scott Smith at ThingsCon](https://raw.githubusercontent.com/understanding-the-connected-home/book/master/img/talk_scottsmith.png)](https://www.youtube.com/embed/CjcJfGrWKNA)

As Scott points out starting around the 27 min mark (but we strongly recommend watching the whole talk), it's crucial to think about the legacy of UX decisions, business models, etc., to explore the different cross-impacts, the implications.

> "Can we find a way to surface and make legible the tensions and the frictions and the conflicts that arise when new connected, data-collecting objects are introduced into our world?"

For now, just assume that putting several smart agents/appliances to work side by side might yield unintended consequences. These might not be devastating - most likely they're simply annoying, like lots of notifications on your phone or shutters that open and close seemingly at random. 

**As connectivity becomes more deeply engrained in our physical environments - homes, vehicles, bodies, cities - we better figure out how to make all these agents work together smoothly: In our interests, by our standards, and to augment rather than simply automate.**
