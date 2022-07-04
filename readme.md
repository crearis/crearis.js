Crearis.js
==========
Website-Starter for interconnected websites in the field of NGO-work focussed on: drama-in-education / community theatre / playing arts / activism / ... and many more

### Status: drafting, experimental work, developer-relations

### Roadmap
Oct 2022: Proof-of-Concept
Jan 2023: Alpha
Q2 2023: Beta
~Q4 2023: RC > Production

### Preview expected by dec 2022!!
The project starts by creating a reference-implementation to connect about 15 organisations and freelancers in the field of 'Theaterpädagogik', mainly located in Bavaria/Germany.

### Overview
Crearis.js is coded in vue3-nuxt3 and implements logic to surface distributed and decentralized content on multiple websites.
At the core it runs a markdown-processor which is able to integrate and render distributed sources within the user-browser. Each node of the network-of-websites renders a static version, which represents a localized view on the distributed data. This is for instance the home-page of an organisation, that is participating

To achieve this, first of all it leverages nuxt/content-module and some additional logic from projects like .
Secondary recources:
- schema.org


- other resources drawing on remark/rehype (like: stripe/markdoc > variables, functions? ...)


Licence: MIT
