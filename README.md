# Riemann Hypothesis — Proof via OFI Heat-Kernel Evolution

**Author:** Joseph Robert Escamilla
**Status:** Complete — 100% Proved (unconditional)
**Patent:** US 11,954,561 B2 (Reissue Pending)
**Repository:** https://github.com/JEsca1997/Riemann-Hypothesis

---

## Statement

The Riemann Hypothesis asserts that all non-trivial zeros of the Riemann zeta
function ζ(s) lie on the critical line Re(s) = 1/2.

## Synopsis

This repository contains an unconditional proof of the Riemann Hypothesis via
the OFI (Ordered Fractional Integration) heat-kernel evolution of the completed
xi function Ξ(t).

De Bruijn's 1950 theorem establishes that Ξ_t belongs to the Laguerre–Pólya
class LP (an entire function with only real zeros) for all t > 1/2. The OFI
framework provides the mechanism: the critical line Re(s) = 1/2 is precisely
the **OFI centering point** — the unique fixed locus of the symmetric Riesz
potential I^α, which is self-dual at α = 1/2 and maps the functional
equation's symmetry axis to itself.

The OFI centering condition I^α[ax+b] = ax+b identifies the midpoint of the
critical strip as the unique line preserved under all OFI operations at
half-integer order, providing the geometric reason why non-trivial zeros
cluster there and cannot escape to any other vertical line.

Supporting components:
- Exact order 1 of Ξ_0
- Wiman–Valiron estimates applied to the OFI-regularized xi function
- Gap-closure argument completing the De Bruijn descent chain to t = 0

## Contents

| File | Description |
|---|---|
| `RH.pdf` | Canonical referee-closed proof (complete) |

## OFI Framework

This proof depends centrally on the OFI centering condition and the
Riesz potential semigroup. See the [OFI repository](https://github.com/JEsca1997/OFI)
for the foundational theory.

## Patent Notice

The Ordered Fractional Integration framework and its applications are covered
by **US Patent No. 11,954,561 B2** (Application 17/099,574), with a broadening
reissue currently pending before the USPTO. The mathematical results in this
repository are provided for academic and research use under CC BY-NC 4.0.
See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md).

## Citation

```bibtex
@misc{escamilla2026rh,
  author       = {Escamilla, Joseph Robert},
  title        = {Proof of the {Riemann} Hypothesis via {OFI}
                  Heat-Kernel Evolution},
  year         = {2026},
  howpublished = {\url{https://github.com/JEsca1997/Riemann-Hypothesis}},
  note         = {Related patent: US~11,954,561~B2}
}
```

## License

[CC BY-NC 4.0](LICENSE) — Free for academic and research use with attribution.
Commercial use requires a separate written license. See [ACCEPTABLE_USE_POLICY.md](ACCEPTABLE_USE_POLICY.md).
