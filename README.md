# LaTeX-motifs

METAFONT and LaTeX code for drawing network motifs as inline characters.

Please check your local methods for running metafont, but the following works on OSX 12.6.3.

```
> mf-nowin '\\mode=ljfour; mode_setup; input motifsymbols.mf'
> gftopk motifsymbols.600gf motifsymbols.600pk
```

These fonts were developed for the work:
House, T., Davies, G., Danon, L. and Keeling, M. J., 'A Motif-Based Approach to
Network Epidemics.' *Bull. Math. Biol.* **71**, 1693–1706 (2009).
https://doi.org/10.1007/s11538-009-9420-z
