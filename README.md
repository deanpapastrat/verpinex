# Verpinex
An open source, easy, rapid, and modern web page builder that runs 100% in the browser, no coding required.

## Team
__Lead Developer__: Dean Papastrat (Georgia Tech/Sideqik): [@deanpapastrat](https://github.com/deanpapastrat)

*We want more people to join us! Open an issue or write a comment on a file and tell us if you would like to participate.*

## Development Plan
1. Design UI and UX in Sketch. Refine user stories and perfect the experience on an abstract level.
2. Review user stories with marketers, designers, and non-technical people. Find the places they don't understand and simplify.
3. Model the data while keeping future ideas in mind, to make it easily scalable and expandable. Make it easy to integrate with a typical REST API so that Verpinex could eventually sync to a server as well as the browser.
4. Initialize the main project files using Ember.js and PouchDB
5. Write all low-level operations and build helpers that abstract it so the UI is simple and clean.
6. Write the HTML/JS/CSS exporter. Test it extensively with practice data. Refine any issues with models. (use Blob API/saveAs)
7. Make wrapper interface, including home, index, etc.
8. Make page editor.
9. Make site editor.
10. Finish loose ends.
11. Alpha release.
12. Fix all bugs from alpha.
13. Beta release.
14. Fix all bugs from beta, add some features from feature requests.
15. Release v1.0.0

## Planned Additions
### v1.1
- Add global events system so that users can develop their own programs that rely on data generated in Verpinex.
### v2.0
- Add official client-side API for retrieving data from Verpinex.

## Planned Parallel Projects
### Verpinex S
Verpinex S will be a lightweight server for serving Verpinex. Initial plans would call for a design based on Sails.js, using WebSockets to push data back and forth in realtime. The Verpinex client would sit on top and work as usual, but the PouchDB would sync to the server at various intervals.
### Verpinex JaRuPyN (Java, Ruby, Python, Node, pronounced "Jar-Rue-Pine")
Verpinex JRPN will be a project for extracting the core HTML rendering functionality from Verpinex and converting it to other languages. This way, server-side programs can use the data provided by Verpinex on the client side and static pages to cloud hosting services, serve Verpinex data itself, etc.
### Verpinex E
Verpinex E will be a jQuery or JavaScript plugin that you can use to easily integrate Verpinex with your existing site.

## Acknowledgements
2015, MIT License.
