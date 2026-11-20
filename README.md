# graszp.info
Static HTML for https://graszp.info: the Badinagean Nomenclature, the philosophical vocabulary of Victor Badinage, published as a SKOS concept scheme in JSON-LD with permanent concept IRIs.

It is the reference case of the [graszp](https://graszp.com) solution architecture method.

- `/<key>/`: a concept's permanent IRI; redirects to its latest version
- `/<version>/`: one frozen release (0.0.1 onward); `/<version>/<key>/` is a concept as it stood in that release
- `/concept-scheme/`: the scheme's permanent IRI
- `/nomenclature/about/`: about the nomenclature

The pages are generated from an Obsidian vault by [jklemke/obsidian_to_jsonld](https://github.com/jklemke/obsidian_to_jsonld); do not edit them by hand. Releases 0.0.1 to 0.0.8 were first published at https://vernacular.cloud and are kept here unchanged; every old vernacular.cloud address redirects to the same path here, and each permanent IRI page carries `owl:sameAs` its old IRI.

Deployed by AWS Amplify from the `main` branch.

Copyright © 2026 Vernacular Cloud LLC.
