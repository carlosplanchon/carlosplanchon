## Hi there 👋

I'll never forget the moment computers first gripped my imagination. It was 2005, and I was seven years old, sitting at my aunt's computer, clumsily experimenting with PowerPoint. Suddenly, the program froze. Intrigued but unsure what to do, I called over my cousin Victoria, who declared with authority that a virus had infected the machine. My mind reeled: Could computers get sick like people?

She explained, in the dramatic way only a teenager could, that these viruses were tools of "shadowy hackers" who could do all kinds of things through a computer. To my young self, this was earth-shattering. How could lines of code do that? How could a machine, this box of buttons and beeps, hold such power or vulnerability? That day sparked a lifelong obsession.

A few years later, in 2008, I wrote my first lines of code. I've been using it to explore ideas and tell stories ever since.

These are some of the lineages that run through my work.

## Open identity and digital signatures

[**FirmaUY**](https://github.com/carlosplanchon/firmauy) is at the centre of my current open-source work, bringing the Uruguayan electronic ID to the terminal for local signing and verification with open and auditable tooling.

That work extends into [firmauy-mcp-inspect](https://github.com/carlosplanchon/firmauy-mcp-inspect), [signing-attestations](https://github.com/carlosplanchon/signing-attestations), and my contributions to [OpenSC](https://github.com/OpenSC/OpenSC), where I [added end-to-end support](https://github.com/OpenSC/OpenSC/pull/3729) for the Uruguayan electronic ID through a dedicated card driver and synthetic PKCS#15 implementation, giving open-source software a standard PKCS#11 path to the card for certificate access, PIN verification, digital signatures, and [public identity data](https://github.com/OpenSC/OpenSC/pull/3747). This removes the need for applications to depend exclusively on proprietary middleware and provides an open foundation for building identity and signing tools around Uruguay's national eID. [Nicolás Gutiérrez](https://github.com/nicolasgutierrezdev) contributed multi-batch testing and card identification work.

[gencedula](https://github.com/carlosplanchon/gencedula) reaches further back, growing out of a script I wrote in 2014 to verify Uruguayan cédula check digits before being published as a repository in 2019.

## Arch Linux and terminal environment

My reproducible Arch Linux workstation and terminal environment are defined in [sway-workstation](https://github.com/carlosplanchon/sway-workstation), [zsh-classic-stack](https://github.com/carlosplanchon/zsh-classic-stack), and [starship-p10k-rainbow](https://github.com/carlosplanchon/starship-p10k-rainbow).

## Backend systems

I contribute to [**FastAPI Boilerplate**](https://github.com/benavlabs/FastAPI-boilerplate), a batteries-included foundation for production FastAPI applications, alongside [Igor Benav](https://github.com/igorbenav), whom I had the pleasure of meeting in Rio de Janeiro.

## Market microstructure

[**measurevolume**](https://github.com/carlosplanchon/measurevolume) grew out of a cross-exchange arbitrage system I worked on in early 2020, using order-book snapshots to estimate market-taker pressure from visible depth depletion. The analysis accounts for differences in published book depth through comparable observation windows, price bands, confidence tiers, and equal-window controls.

## Browser agents

I contributed lifecycle hooks to [**Browser Use**](https://github.com/browser-use/browser-use), adding `on_step_start` and `on_step_end` extension points around each agent step. These hooks let developers instrument, observe, and customize agent execution without modifying the core execution loop, enabling use cases such as tracing, policy enforcement, dynamic control, and integration with external systems. The hooks are now part of Browser Use's public API, and I also wrote their [official documentation](https://docs.browser-use.com/open-source/customize/hooks).

## Aviation

I've also made a couple of projects related to aviation: a [weight and balance calculator](https://github.com/carlosplanchon/weight-and-balance-calculator-piat) and a [takeoff performance calculator](https://github.com/carlosplanchon/takeoff-performance-calculator-piat) for the airplane I fly, the Pipistrel ALPHA Trainer.

## Website preservation and reconstruction

My work in website preservation began in 2018, with experiments in copying, preserving, and reconstructing websites.

The [**SpiderCreator**](https://github.com/carlosplanchon/spidercreator) line started in 2019 from the code of [iww](https://github.com/MohamedHmini/iww), created by [Mohamed Hmini](https://github.com/MohamedHmini), and developed from that technical starting point over the following years.

## Tools

[**outfancy**](https://github.com/carlosplanchon/outfancy) was the first library I built, in 2014, when I was sixteen.

[**xmlstreamer**](https://github.com/carlosplanchon/xmlstreamer) is a streaming parser I built for huge and unreliable XML feeds. It keeps memory bounded, isolates localized corruption instead of losing the whole feed, and makes partial failures explicit rather than silently repairing damaged input into data that was never there.

Other projects include [worldclock-tty](https://github.com/carlosplanchon/worldclock-tty), [plotilleresample](https://github.com/carlosplanchon/plotilleresample), [tokenizesentences](https://github.com/carlosplanchon/tokenizesentences), [ifpeek](https://github.com/carlosplanchon/ifpeek), [deblotch](https://github.com/carlosplanchon/deblotch), and [checkcorruptedimages](https://github.com/carlosplanchon/checkcorruptedimages).

## Open source community

Through [LibreCourseUY](https://librecourse.uy), which I co-lead with its founder, [Emiliano Gandini](https://github.com/emiliano-go), I help promote open-source software, technical learning, and collaboration in Uruguay.

Outside of code, I row and fly, and occasionally contribute [aerial photography](https://commons.wikimedia.org/wiki/Special:ListFiles/Carlosplanchon) of Uruguay to Wikipedia. 🚣🛩️📷

<!--
**carlosplanchon/carlosplanchon** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
