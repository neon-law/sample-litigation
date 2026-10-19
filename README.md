# Navigator Sample Project — Litigation

The sample Project repository for the fixture matter *Cruller v. Prine*: a dispute in front of a court: a trespass count
and a claim to rescind the doughnut instrument.

It is one of three, each a different shape of legal work: [litigation](https://github.com/neon-law/sample-litigation),
[transactional](https://github.com/neon-law/sample-transactional), and
[estate](https://github.com/neon-law/sample-estate).

**Everything here is fixture data.** *Cruller v. Prine* is a simulated matter, and nobody named in this repository is a
real person. No client data belongs in it, ever.

## What is here

* `navigator.yaml` names the Project and declares its matter pages under `pages:`. Navigator renders each page at
  `/app/projects/sample-litigation/<slug>`, from the records it stores on the matter, for the reader's own lens.
* `drafts/` holds the matter's Drafts. An activated Draft is a Notation.

The repository carries no application code. The only tool it uses is the `navigator` release that `navigator.yaml` pins.

## Check it

```bash
navigator project gate
```

## See it locally

From a Navigator checkout, `navigator dev sample-project --project sample-litigation` clones this repository and stages
its manifest and Drafts; the next local boot stores the pages and opens the Notations.
