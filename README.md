# mergesutra-e2e-fixture

A deliberately tiny package: one function (`slugify`), one test file, one npm
script. It exists so that MergeSutra's `issue → inspect → contract → plan →
implement → verify → review → report → pr` flow can be exercised against a real
GitHub repository whose whole behaviour is checkable in a second.

Run the gate with:

```bash
npm test
```

`src/slugify.js` keeps its current edge-hyphen behaviour on purpose; see the
open issue for the change that is expected of it.
