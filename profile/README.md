# NeuroTestix

**Local-first ML research for reproducible Python bug discovery.**

We are building a compact, trainable model that examines an approved repository snapshot, proposes a falsifiable behavior hypothesis, and writes a pytest counterexample. A separate offline runner checks the test on the buggy and fixed revisions; a human reviewer decides whether the behavior is a defect.

The project is in early research. We have not trained a NeuroTestix checkpoint or demonstrated an advantage over existing models. Product repositories remain private while we validate data rights, evaluation boundaries, local runtime cost, and the model itself. We intend to publish the open-source work after those checks.

Our first technical milestone is a reproducible small-model training run. The product milestone is a blind, repository-separated evaluation with independently accepted root causes and a measured false-alert budget.
