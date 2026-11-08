# Vinciolo's Lace

**https://guillochon.github.io/vinciolo-lace/**

Federico de Vinciolo was a Venetian lace designer working in Paris around 1600. His pattern book *Les Secondes
Oeuvres, et Subtiles Inventions de Lingerie* (Paris, 1603) prints dozens of charts for *lacis*, lace made by darning
chosen meshes of a square net. This page traces the 19 fully symmetric square panels in the book and finds the one
rule they never break: no open mesh is walled in on all eight sides by darned meshes. Of the 512 possible 3 × 3
patches, the panels use every other one.

Counting the symmetric n × n designs that obey that rule gives a new integer sequence:
1, 2, 6, 7, 48, 55, 705, 861, 21454, 26696, … (n = 1, 2, …). Without the symmetry it is OEIS
[A202788](https://oeis.org/A202788). The terms to n = 47, the method and every check are in
[oeis-results/vinciolo-lace](https://github.com/guillochon/oeis-results/tree/main/vinciolo-lace).

The page has:

- **The artist and the book**, with plates from the Metropolitan Museum's copy.
- **From woodcut to grid**: the photograph of page 37 and its traced grid.
- **The 19 symmetric panels**, traced and symmetrized.
- **The rule**: the rarest 3 × 3 patterns in the panels, and the one that never occurs.
- **Try it**: a symmetric editor that marks pinholes, draws random designs obeying the rule, and loads any of
  Vinciolo's panels.
- **The sequence**: definition and the table of a(1)–a(47).

Everything runs in the browser from one file (`index.html`) plus the plate images in `img/`.

Images: Federico de Vinciolo, *Les Secondes Oeuvres*, Paris, 1603; The Metropolitan Museum of Art, Harris Brisbane
Dick Fund, 1939 (39.30), public domain via the Met's Open Access program.

Made by James Guillochon with Claude. The source lives in the oeis-sniper project (`viz/vinciolo/`); this repo holds
the published copy.
