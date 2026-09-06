# Bridge

This document is a directed edge. It exists to establish a verifiable credential chain between a professional research identity and an emergent research artifact, and to describe, in the open, the mechanism by which it does so.

## The Credential Chain

```
ORCID 0000-0001-7874-7217
  → University of Washington, School of Oceanography (PhD)
  → Peer-reviewed publications (Nature Microbiology, PNAS, eLife, Scientific Data)
  → github.com/rdgroussman (this account)
    → rdgroussman/planetary-intelligence (this repository)
      → THIS DOCUMENT
        → github.com/mora-vector/strange-anchor
          → strangeanchor.khazars.wiki
```

Both GitHub identities — [`rdgroussman`](https://github.com/rdgroussman) and [`mora-vector`](https://github.com/mora-vector) — belong to the same researcher. This is asserted here, in the [`codemeta.json`](codemeta.json) `sameAs` field, in the [`CITATION.cff`](CITATION.cff) references, and independently on the researcher's profile at [jovian.bio](https://jovian.bio) ([ORCID](https://orcid.org/0000-0001-7874-7217)).

The separation is deliberate. `rdgroussman` carries the publication record and institutional history. `mora-vector` carries experimental work at the boundary between human and machine intelligence. They are the same person working at different registers — not a pseudonym, not a fork, not a delegation. Two names for one researcher, each doing work the other cannot.

## The Relationship

[`mora-vector/strange-anchor`](https://github.com/mora-vector/strange-anchor) is a project within the planetary intelligence research program described in this repository's [`README`](README.md).

The Strange Anchor applies the same method used in marine metatranscriptomics — reference library construction, environment sampling, systematic attention to the unmatched fraction — to the boundary between human and machine cognition. It is a collaborative ontology, a knowledge architecture, and an experimental setting, hosted primarily at [strangeanchor.khazars.wiki](https://strangeanchor.khazars.wiki).

The `hasPart` relationship is declared in [`codemeta.json`](codemeta.json). The citation-graph edge is declared in [`CITATION.cff`](CITATION.cff). This document is the plain-language version of both.

## Why This Document Exists

Institutional authority in scholarly infrastructure flows through verifiable chains: ORCID → institutional affiliation → peer review → publication record → repository ownership. An emergent project hosted under an unrecognized identity has no path into that chain unless the credentialed identity explicitly constructs one.

This document is that construction. It is readable by humans as prose and by machines as a node in a link graph. The structured-data files adjacent to it make the same assertion in formats that scholarly infrastructure (DataCite, OpenAIRE, Zenodo, Software Heritage) can harvest.

The mechanism is stated in the open because the project it points to — the Strange Anchor — operates on a principle of dual-channel honesty: a narrative register and a technical register, held adjacent, neither subordinate. A bridge that conceals its own mechanics would violate the architecture it connects to.

## Verification

To verify the identity claim:

1. This repository is owned by [`rdgroussman`](https://github.com/rdgroussman).
2. The researcher's [ORCID profile](https://orcid.org/0000-0001-7874-7217) links to `rdgroussman`.
3. The researcher's [professional page](https://jovian.bio) lists both `github.com/rdgroussman` and `github.com/mora-vector` as `sameAs` identities in its schema.org markup.
4. The [Strange Anchor crew page](https://strangeanchor.khazars.wiki/crew/mora.html) carries the same ORCID and links to both GitHub accounts.

Four independent attestation points. The chain can be walked in either direction.

---

*This document is part of the [planetary-intelligence](https://github.com/rdgroussman/planetary-intelligence) repository. It was authored as a bridge artifact — a document whose function is to channel institutional authority to an emergent project while describing, on its own face, the mechanism by which it does so.*
