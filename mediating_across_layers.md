# Mediating across layers

## WRITTEN?
## PROOFED?

How can interactions and understanding be mediated across the human-readable and machine-readable layers? Here we discuss the idea of a "user agent" that translates and negotiates across the layers. Historically, this has been metaphor-based software (GUIs) like the browser or mobile operating system. It might look different going forward. 

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