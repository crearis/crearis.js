Crearis.js
==========
Website-starter to build a network of websites. Each of those websites modelling a life-cycle of 'creative events' together they enable decentralized NGO-networking.


Main focus on: drama-in-education / community theatre / playing arts and similar communities of creative work (music, activism, performance ...)

### status: drafting
- experimental work


- rebuilding core from vue2/nuxt2-project


- developer-relations

### roadmap
- Oct 2022: Proof-of-Concept


- Jan 2023: Alpha + Preview (~10 connected website-projects running the code)


- Q2 2023: Beta


- ~Q4 2023: RC > Production

### vision
In short Crearis wants to enable open-source-like cooperation in the fields of creative work: A network of distributed content, decentralized projects and events, connected both regionally (in-person-events) and thematically (virtual communities). Crearis helps the participants of the network to (re)build  their websites based on modern standards:
- coded in vue3-nuxt3


- clients designed with tailwind (desktop-focussed) and vuetify (mobile-focussed)


- implementing web3-style-logic to surface distributed and decentralized content on multiple websites ('web3' mainly in the terms of decentralization, collective organization. Not as a reference to a certain blockchain-technology. Not as a reference to some sort of 'big money scheme').

### technical idea
At the core Crearis runs a markdown-processor which is able to integrate and render distributed sources within the user-browser. Each node of the network-of-websites renders a static version, which represents a localized view on the distributed data. This is for instance the home-page of an organisation, that is participating in the network and houses creative events and serves the data for those events. 


1. Through Crearis this organisation is able to crosspost and co-publish those events with events of partnering organizations and freelancers.


2. Through Crearis users attending events of connected organizations can have their own perspective rendered in their browser: The events they attend, their communication with other users, projects ...



### technical foundation
Crearis leverages the nuxt/content-module and some additional logic from projects like .:
- schema.org


- userbase.com


- other resources drawing on remark/rehype (like: stripe/markdoc > variables, functions? ...)


### background
This is an opinionated project. We start from Europe:
- focus on privacy (non-tracking ..)


- a long tradition of creative collectives in mind like ‘der blaue Reiter’ (pseudonymous work) or the ‘Brecht Kollektiv’ (integrating theatre with modern thinking and modern technologies)


- want to help creative collectives and community actions to develop reach and visibility on the internet 


- want to help to achieve this without having to feed the big business models of social media


- target questions like ‘liquid democracy’ and ‘participation’


The initial project will serve as reference-implementation and should be reachable ~nov 2022 at theaterpedia.org. It connects about 15 organisations and freelancers in the field of 'Theaterpädagogik', mainly located in Bavaria/Germany.


### Licence: MIT
