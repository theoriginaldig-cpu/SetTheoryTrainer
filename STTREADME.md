# Set Theory Trainer

A browser-based practice tool for reasoning about sets: subsets, proper subsets, intersections, unions, differences and the empty set.

Each question gives some premises and asks whether a conclusion follows. Questions come in two styles:

- **Set notation:** for example, *X* ⊆ *Y* and *Y* ⊂ *A* ∩ *B*; does it follow that *X* ⊂ *A*?
- **Predicates:** for example, all *F*s are *G* and some *G*s aren't *H*; does it follow that {*x*: *Fx*} ⊂ {*x*: *Hx*}?

Students first say whether the conclusion follows. If it doesn't, they build a counterexample by ticking which numbered objects belong to which sets, and the app checks it. Every question has a model answer:

- **When the conclusion follows:** an element-by-element proof, with a Venn diagram showing what the premises say.
- **When it doesn't:** a smallest counterexample, with a Venn diagram showing the counterexample.

## Using it

Open the site's link in any web browser. Nothing needs to be installed, and no sign-in is required. Scores are kept only in the student's own browser, and no data is collected or sent anywhere.

## Files

- `index.html`: the whole app, in a single self-contained file.

## Updating

Upload a new `index.html` to replace the old one. The site's address stays the same.
