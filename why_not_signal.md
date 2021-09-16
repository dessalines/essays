# Why not Signal?

## Contents

<!-- toc -->

- [Why not Signal?](#why-not-signal)
  * [The Problem](#the-problem)
  * [Enter Signal](#enter-signal)
  * [What's wrong with Signal?](#whats-wrong-with-signal)
    + [CIA Funding](#cia-funding)
      - [CIA → RFA → OTF → Signal](#cia-%E2%86%92-rfa-%E2%86%92-otf-%E2%86%92-signal)
    + [A Single, Centralized, US-based service](#a-single-centralized-us-based-service)
      - [National Security Letters (NSLs)](#national-security-letters-nsls)
    + [Phone # Identifiers](#phone-%23-identifiers)
    + [Social network graphs](#social-network-graphs)
    + [Abandonment of Open source](#abandonment-of-open-source)
    + [Bundling a Cryptocurrency](#bundling-a-cryptocurrency)
    + [Others](#others)
  * [What makes a good messaging platform?](#what-makes-a-good-messaging-platform)
    + [End-to-end encrypted](#end-to-end-encrypted)
    + [Open Source](#open-source)
    + [Self hosted](#self-hosted)
    + [Federated](#federated)
    + [No required linkable identifiers](#no-required-linkable-identifiers)
  * [Bad Alternatives](#bad-alternatives)
  * [Good Alternatives](#good-alternatives)
    + [Matrix](#matrix)
      - [Caveats of federation: Metadata leaking](#caveats-of-federation-metadata-leaking)
    + [XMPP](#xmpp)
      - [Caveats](#caveats)
    + [Briar](#briar)
      - [Caveats](#caveats-1)
    + [Jitsi](#jitsi)
  * [Conclusions](#conclusions)

<!-- tocstop -->

# Why not Signal?

About me: While I'm no cryptography expert, I'm a software developer with 10+ years of experience, both in the professional and open source world. Currently I'm a lead developer for a popular open source federated software called [Lemmy](https://github.com/LemmyNet/lemmy). My perspective and recommendations here come from being an active participant in open source communities.

## The Problem

After the [global surveillance disclosures of 2013](https://en.wikipedia.org/wiki/Global_surveillance_disclosures_(2013%E2%80%93present)), finding a secure messaging platform to replace text messages became an imperative for all activists. It was found that US, Canadian, UK, Australian, and New Zealand intelligence agencies (the ["Five Eyes"](https://en.wikipedia.org/wiki/Five_Eyes)), along with US tech giants like Facebook, Apple, Google, and Microsoft, were collecting and forwarding email, text, voice, and video chats to governments, **without any warrant required.** 

Western governments created a worldwide system of surveillance that *even their own citizens and allies* could seemingly not escape from. 

It was also long known that communications within walled gardens like Facebook or Gmail were not secure, so many players around this time began to develop secure messaging alternatives. 

## Enter Signal

[Signal](https://signal.org/en/) became one of the first platforms to develop and use an end-to-end-encryption (E2EE) system and open standard, which many other platforms adopted or modified for their own use.

It also became widely popular for integrating seemlessly with your existing contact list and message history. Its features include voice calls and messages, attachments, replies, and group chats.

Over the years, its been increasingly used by activists, journalists, and politicians alike, and endorsed by western privacy advocates like [Edward Snowden](https://www.indiatoday.in/technology/news/story/how-secure-is-signal-it-s-good-enough-for-edward-snowden-so-good-enough-for-you-1757596-2021-01-10), and [Bruce Schneier](https://www.schneier.com/blog/archives/2016/12/how_signal_is_e.html). It also has several questionable endorsements and users, such as Jack Dorsey (Twitter's founder), and [Elon Musk](https://www.theverge.com/2021/1/7/22218989/signal-new-signups-whatsapp-facebook-privacy-controversy-elon-musk).

Until a few years ago, it was seen as an underdog, and the best secure alternative to the ["Big Five"](https://growthrocks.com/blog/big-five-tech-companies-acquisitions/) US tech giants. Its history and deficiencies, which were always out in the open, and which I'll get into below, were overlooked due to its underdog status in the tech world, its courting of the open source community, and its colorful anarchist founder, [Moxie Marlinspike.](https://www.wired.com/2016/07/meet-moxie-marlinspike-anarchist-bringing-encryption-us/)

In January 2021, after WhatsApp, the most popular messaging app in the world, became acquired by Facebook, and announced its sharing of data with its new parent, [Signal became the top downloaded app in > 70 countries.](https://archive.is/NdCxm)

Signal's exploding popularity among messaging apps, has lead many activists to re-open signal's case, and consider why a "secure" yet popular platform has garnered little to no response from US government officials. 

As it turns out, the US government was (and possibly remains) itself a primary funder of Signal.

## What's wrong with Signal?

### CIA Funding

#### CIA → RFA → OTF → Signal

[While this article by Yasha Levine gets into the details](https://archive.is/Rz6Qa), it is no secret that the original funder of [Open Whisper Systems](https://en.wikipedia.org/wiki/Open_Whisper_Systems) (the previous name for signal's development team), was the [Open Technology Fund](https://en.wikipedia.org/wiki/Open_Technology_Fund): itself publicly listed as a subsidiary of [Radio Free Asia](https://en.wikipedia.org/wiki/Radio_Free_Asia), a US state-run organization whose main goal (along with the other "Radio Free" incarnations such as Radio Free Europe, or Free Cuba Radio) is regime change for those Asian governments who don't align with the US's foreign policy interests.

The Radio Free agencies underwent a public re-branding in the early 1990s, but [they are in effect the same CIA misinformation organizations from the 1950s:](https://www.nytimes.com/1977/12/26/archives/worldwide-propaganda-network-built-by-the-cia-a-worldwide-network.html)

> Radio Free Asia began broadcasting to mainland China in 1951 from an elaborate set of transmitters in Manila. It was an arm of the Committee for Free Asia, and the C.I.A. thought of it as the beginning of an operation in the Far East that would rival Radio Free Europe and Radio Liberty.
>
> It was only after Radio Free Asia's transmitters were operating, according to sources familiar with the case, that the C.I.A. realized that there were almost no radio receivers in private hands in mainland China. An emergency plan was drawn up. Balloons, holding small radios tuned to Radio Free Asia's frequency, were lofted toward the mainland from the island of Taiwan, where the Chinese Nationalists had fled after the Communist takeover of the mainland in 1949. The plan was abandoned when the balloons were blown back to Taiwan across the Formosa Strait.

What Allen Weinstein, one of the founders of the National Endowment for Democracy (NED), another US "human rights" regime change org said of his organization applies equally to the Open Technology fund: “A lot of what we do today was done covertly 25 years ago by the CIA.” 

The fund is designated to: ["support open technologies and communities that increase free expression, circumvent censorship, and obstruct repressive surveillance as a way to promote human rights and open societies."](https://www.opentech.fund/about/values-principles/) 

One should question the commitment of a fund that dedicates itself to "obstructing surveillance", while being created by a government who runs the most expansive surveillance system in world history. And how the US might define the terms "human rights", and "open society" differently from those who know the US's history in those areas.

Its a clear case of US government funding projects with the goal of either co-opting them, as in Signal's case, or absorbing them entirely; in essence, subverting the goals of privacy advocates and developers, by offering them the funding that no one else will provide: as long as they play ball with US interests.

Signal could very well be another Crypto AG-style [honeypot](https://en.wikipedia.org/wiki/Honeypot_(computing)): the Swiss company which provided secure communications services to ~120 governments throughout the 20th century, and was [secretly ran by the CIA and West German Intelligence.](https://archive.is/va2l7)

---

Signal's use luckily never caught on by the general public of China (or the Hong Kong Administrative region), whose government prefers autonomy, rather than letting US tech control its communication platforms, as most of the rest of the world naively allows (For example, India's most popular social media apps, are Facebook and Youtube, meaning that US surveillance giants own and control the data of a country much larger than their own). Signal instead became used by US and western activists, and due to the contradictions of surveillance capitalism, also now its general populace.

However this is no case of [blowback](https://en.wikipedia.org/wiki/Blowback_(intelligence)), [Marlinspike's confused and useful idiot politics aside](https://lemmygrad.ml/pictrs/image/n9o9bNI6gp.jpg); Signal's other deficiencies mean that there are less impediments to US government surveillance over it than previously thought, and make its claims to being "secure", questionable. 

As the above article states, after Yasha Levine wrote an article exposing signal's funding sources, the [RFA tried to do damage control on Signal's behalf,](https://archive.is/Rz6Qa) in the hope that Signal would maintain good relations with its open source supporters, and remain a viable "privacy-oriented" alternative. Libby Liu, president of Radio Free Asia stated:

> Our primary interest is to make sure the extended OTF network and the Internet Freedom community are not spooked by the [Yasha Levine's] article (no pun intended). Fortunately all the major players in the community are together in Valencia this week - and report out from there indicates they remain comfortable with OTF/RFA. 

Clearly the US government was interested in Signal's continued use and expansion.

The reason the US government hasn't tried to block or hinder Signal, *is because it's satisfied with the amount of information Signal can provide to it.*

### A Single, Centralized, US-based service

#### National Security Letters (NSLs)

The US has an [interesting law](https://en.wikipedia.org/wiki/National_security_letter) that applies to *any US company* operating within its borders: it is **illegal to tell your users that the the US government has asked your company to spy on their behalf.** This is called a [key disclosure law](https://www.privacyguides.org/providers/#kdl), and the US's version of it, called [National Security Letters](https://en.wikipedia.org/wiki/National_security_letter), underwent an expansion in with the PATRIOT act.

Companies that don't comply with this law, [such as Lavabit, are forced to shut themselves down in protest, in order to avoid prison time](https://www.youtube.com/watch?v=spW0q-g2BxU), or remain open, and funnel user communications to the US government. Signal is a US domiciled company, and must comply with this law.

Signal also interestingly **isn't self-hostable**: there's no way to run your own signal server, and control your data. [Marlinspike ruthlessly shuts down anyone attempting to build alternate clients or servers that could communicate with the main one.](https://github.com/LibreSignal/LibreSignal/issues/37#issuecomment-217211165) [2](https://github.com/LibreSignal/LibreSignal)

This means that all of Signal's data is centralized and controlled **by a single entity**: a giant and easy target for US surveillance.

The centralization of Signal's data, means that it most likely has been issued an NSL letter, along with every other centralized messaging company domiciled in the US. While it's impossible for us to know for certain, its also illegal for the founders to disclose that. For a threat analysis, we should assume the worst, especially for such a popular app.

This could account for many Signal developers' characterization of [Marlinspike as being paranoid, and a control-freak](https://archive.is/NdCxm) when it comes to some of Signal's administration. Marlinspike could face real prison time if this information were *even accidentally* made public.

In a time where nearly all new messaging platforms are using the self-hosted+federation model, [Marlinspike came out staunchly in favor of centralization](https://signal.org/blog/the-ecosystem-is-moving/), and refused to consider federation when asked by the developers of Matrix, a federated messaging protocol, on the grounds that it would slow down feature development. [Their response is here](https://matrix.org/blog/2020/01/02/on-privacy-versus-freedom).

### Phone # Identifiers

If you were building a secure platform, and wanted to use an identifier, what would be the worst thing to use? **Phone numbers.**

Phone numbers in nearly every country, including the US, **are directly linked to your identity**: including your full name, social security number, and even current address. A simple reverse phone number lookup, *doable even by non law enforcement actors*, can reveal this information.

This is also why it's impossible for anonymous or Internet-only activists to use Signal: by giving others their phone number, they give away their full name and address.

[Privacy advocates stress that services need to minimize "linkability"](https://www.youtube.com/watch?v=ACI7zZGgi80):  the less identifiers that link to your real identity, the better. 

Signal also allows you to be discoverable via your phone number, without your consent. Law enforcement officials frequently add the phone numbers of suspects, or groups of suspects to their own signal app, and signal will happily tell them which of their suspects are using signal.

### Social network graphs

Signal's E2EE protocol means that, most likely, message _content_ between persons is secure. But third parties often care more about *metadata*, than actual content, since they don't have time to manually read through the messages anyway to construct meaning.

Signals database, which we must assume is compromised due to its centralized and US domiciled nature, has a few important pieces of data;

- Message dates and times
- Message senders and recipients (via phone number identifiers)

From these 2 pieces of information, its possible to build social graphs: **who talked to who, and when they did it.** Also, who's in a group chat with who else.

It may not matter to the US government what was said, when they know that 4 activists in the same city, and one from outside sent each other messages frequently on the day of a protest. They now have a list of suspects.

Pair that with cell-phone location data, and you have a timeline profile about a group of connected suspects.

Some Signal advocates have pointed out that signal implements [sealed sender](https://signal.org/blog/sealed-sender/) in a beta version of the program. Anyone who's worked with centralized databases can tell you that with recipient information, and message timestamps, it would be trivial to find the real sender of a message.

### Abandonment of Open source

While Signal's apps and server source code *purport* to be open source, in reality signal has been slow to update them. [In April 2021, signal outraged the open-source community by going a **whole year** without publishing their server code updates.](https://www.androidpolice.com/2021/04/06/it-looks-like-signal-isnt-as-open-source-as-you-thought-it-was-anymore/) After the outcry, signal *finally* updated their server code to appease the open source community, but it left a sour taste in everyone's mouths.

### Bundling a Cryptocurrency

Recently, [signal has been attempting to integrate a cryptocurrency called MobileCoin, into the app itself.](https://cointelegraph.com/news/signal-under-fire-over-mobilecoin-partnership) What a messaging platform has to do with an obscure cryptocurrency is a little vague; but there is probably some money driving this. Since Marlinspike doesn't allow 3rd party clients, it is impossible to avoid these types of unwanted "features".

### Others

[An exhaustive list of other technical concerns is here](https://github.com/privacytools/privacytools.io/issues/779), and [here](https://drewdevault.com/2018/08/08/Signal.html).

## What makes a good messaging platform?

### End-to-end encrypted

The communication between persons or groups of persons should be encrypted in such a way that only the senders and recipients can read the messages. For an explanation of how this works, [watch this video on public key cryptography.](https://www.youtube.com/watch?v=YEBfamv-_do)

### Open Source

The source code for both the server, and client applications should be out in the open, so that the community can contribute: to fix bugs, find security flaws, and suggest features. It should also allow 3rd party clients and server implementations, and be based on an open standard.

### Self hosted

A messaging platform should be able to be run in an entirely private manner, controlled only by the person who has downloaded its software. That person should also be able to build the project from its original source code, ensuring that nothing nefarious was inserted. 

Having full control over your data is extremely important, especially for activists who want to avoid malicious 3rd parties.

### Federated

The best way to describe federation, is to think of email. Many people can sign up on different email services (Gmail, hotmail, etc), yet can still email each other. In the same way, a communications platform should be able to talk with other people running the same software elsewhere.

Peer-to-peer (P2P) is a subset of federated, where instead of anyone being able to run a server, the server is as small as an app. These apps communicate not through servers, but directly with each other.

### No required linkable identifiers

The less identifiers a database has, such as your real name, email, and phone number, the better. These are linkable attributes that only the sender and recipient should know, not the server or any intermediaries.

## Bad Alternatives

The obvious offenders are those companies that have already signed up to the NSA's [PRISM](https://en.wikipedia.org/wiki/PRISM_(surveillance_program)) program. Their applications include Facebook and its messenger, Whatsapp, Instagram, Skype, Microsoft teams, Gmail, Youtube, Apple messages, and cell carrier text and voice calling.

Other disqualified alternatives include US domiciled companies or those with centralized servers, including Signal, Discord, Slack, Zoom, Telegram, Snapchat, Viber, Line, Twitter, and Reddit.

Email is an archaic protocol that [was not designed with encryption or security in mind.](https://news.ycombinator.com/item?id=16088386) Even supposedly ["secure" email providers](https://www.theregister.com/2021/09/07/protonmail_hands_user_ip_address_police/) have been found time and again to be insecure.

Of the criteria for messaging apps above, signal only scores a 1.5 / 5. Most of the apps in this list score a 0 / 5.

## Good Alternatives

The two below are my recommendations, and this is by no means exhaustive. Both of these applications tick all the boxes for what makes a good messaging platform above.

### Matrix

[Matrix](https://matrix.org/) is a self-hostable, federated messaging platform, that within the past few years has come into maturity. Due to its open standard, multiple clients, support for large group chats, and encryption-first design, many are hailing it as the successor to email, and the future of secure communication. 

Its main client, [Element](https://element.io/), has a web app, and full-featured android and iOS apps.

It has many features, including voice / video calls, voice messages, reactions, replies, and spaces (similar to discord's or slack's collection of rooms).

As a testament to its reliability and long-term support, Matrix is even being adopted by some large organizations, and even the [French government](https://matrix.org/blog/2018/04/26/matrix-and-riot-confirmed-as-the-basis-for-frances-secure-instant-messenger-app); It turns out even European governments want to escape the tentacles of US surveillance, and control their data.

#### Caveats of federation: Metadata leaking

When using federation, Matrix's room states (containing a lot of Metadata) get replicated and stored indefinitely on every homeserver any user connects with or connects to. While this is a feature for enabling distributed chat rooms, it comes at a serious privacy cost.

To avoid this, you can either disable federation, or make sure that your users signed up with **no linkable identifiers** other than their user names. 

### XMPP

[XMPP](https://xmpp.org/) is an open standard for messages, that's been around since 1999. It is open source, federated, and has apps for most platforms, such as [Conversations for Android](https://conversations.im/), or [Gajim for desktop.](https://gajim.org)

#### Caveats

XMPP unfortunately suffers from fragmentation, as not all of its clients implement its extension proposals (called XEPs), or its E2EE extensions equally.

### Briar

[Briar](https://briarproject.org/) is an extremely secure P2P chat application, that requires no server: apps communicate directly with each other over the TOR network on the Internet, the same wifi, or through bluetooth.

This makes Briar ideal for the most sensitive communications, such as for sharing personal information, or usage at protests, since it can work during Internet blackouts via bluetooth.

#### Caveats

Briar is newer, and lacks too many features to be usable for large organizations at the moment. There are no voice calls, reactions, permissions systems, or web or iOS clients: its android only at the moment.

### Jitsi

[Jitsi](https://jitsi.org/) is a self-hostable, open source, video-conferencing solution, that can work as an alternative to Zoom. It has a web app, and native apps for desktop, iOS, and android. Matrix currently bundles in Jitsi for use for its video group calls.

## Conclusions

I've outlined here why it's imperative that activist communities migrate away from Signal. We shouldn't be daunted by the inertia that seems to plague general adoption of new chat applications; if our organizations are disciplined enough, and care enough about secure communications, moving to them should be made a priority. 

We must be adaptable and versatile: If in the future, new, more secure alternatives can be found, they should be investigated and considered as alternatives.

We need to take control of our communications, and stop letting US tech companies handle it for us.

