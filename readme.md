Crearis.js
==========
Website-starter for web3-inspired websites to enable decentralized NGO-networking.


Main focus on: drama-in-education / community theatre / playing arts ... and similar types of creative-work-communities in the fields of: music, activism, performance ...

### Status: drafting, experimental work, developer-relations

### Roadmap
Oct 2022: Proof-of-Concept


Jan 2023: Alpha


Q2 2023: Beta


~Q4 2023: RC > Production

### Preview expected by dec 2022!!
The project starts by creating a reference-implementation to connect about 15 organisations and freelancers in the field of 'Theaterpädagogik', mainly located in Bavaria/Germany.

### Vision and core technical idea
In short Crearis wants to enable open-source-like cooperation in the fields of creative work: A network of distributed content, decentralized projects and events, connected both regionally (in-person-events) and thematically (virtual communities). Crearis helps the participants of the network to (re)build  their websites based on modern standards: It is coded in vue3-nuxt3. It implements web3-style-logic to surface distributed and decentralized content on multiple websites ('web3' does not reference blockchain-technology for the moment).

At the core Crearis runs a markdown-processor which is able to integrate and render distributed sources within the user-browser. Each node of the network-of-websites renders a static version, which represents a localized view on the distributed data. This is for instance the home-page of an organisation, that is participating in the network and houses creative events and serves the data for those events. 


1. Through Crearis this organisation is able to crosspost and co-publish those events with events of partnering organizations and freelancers.


2. Through Crearis users attending events of connected organizations can have their own perspective rendered in their browser: The events they attend, their communication with other users, projects ...



### Technical foundation
Crearis leverages the nuxt/content-module and some additional logic from projects like .:
- schema.org


- other resources drawing on remark/rehype (like: stripe/markdoc > variables, functions? ...)


### Licence: MIT
