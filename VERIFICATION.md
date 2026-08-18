# Verification

Measured results for AI Builder Tools.

Every figure came from running the software while the data room was prepared. None of it is copied
out of a document, and each figure is reproducible by a buyer from the delivered files.

---

## Results

| Measure | Value |
|---|---|
| Source files | 113 |
| Source size | about 1.5 MB |
| Built installers | 3, all included |
| Copyleft dependencies | 0 |
| Products with a commercial licence | 3 of 3 |

## Worth knowing

Verified per product rather than by one shared test count: Meta-Brain by release gate and QA suite, Bridgesmith by 6 tests, Ledgerless by a full offline demonstration loop. All three green.

## How this was produced

The software was run from the delivered files. Where a product ships with an installer, the
installer was built. Where a product declares a type check or a build step, both were run. Test
counts are the totals reported by the products' own test commands.

## What is not claimed

A verification record that lists only passes is not a verification record. The package's
open-items document lists every known gap, and it is part of the data room rather than something
a buyer has to discover. Where a test command did not run, where a path went unexercised, or
where behaviour at scale is unproven, the data room says so plainly.

That document is available under a signed non-disclosure agreement, together with the full
verification record and the provenance file. See [ACQUISITION.md](ACQUISITION.md).
