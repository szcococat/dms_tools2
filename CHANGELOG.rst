Change Log
===========

2.2.6
-------
* fix bug in `diffsel.tidyToWide` such that sites with matching values (i.e. all 0 values) are not dropped during de-duplication.

* added `utils.codonEvolAccessibility` function


2.2.5
-------
* fix bug in stringency re-scaling by ``dms2_logoplot``

* fix bug in axis scaling in `plot.plotCumulMutCounts`

* added `Haddox2018` and `Doud2018` examples and doc links

2.2.4
----------
* added `contour` option to `plot.plotCorrMatrix`

* added `white_bg` to `plot.plotSiteDiffSel`

2.2.3
------------
* added `plot.findSigSel`

2.2.2
----------
* added `--bclen2` option to ``dms2_bcsubamp``

2.2.1
---------
* added `protstruct` module for operations related to protein structurs

* added `neutcurve` module to fit neutralization curves

* updated required versions of some dependencies

2.2.0
---------
* added `compareprefs` module

* added `rplot` module to enable plotting with `ggseqlogo <https://omarwagih.github.io/ggseqlogo/>`_

* Added `omega` overlay option to ``dms2_logoplot``

* Fix bug with ``dms2_logoplot`` when using wildtype sequence overlays

* Fix bug with ``--fracsurvivemax 0`` to ``dms2_logoplot``

* Scale pseudocounts when using ``dms2_prefs`` with ``--method ratio``, which should give more accurate values when depths differ across samples.

* Some minor bug fixes.

* Fix bug with handling of disulfide-bonded cysteines in ``dssp`` output.

* Added `colors` option to `plot.plotCorrMatrix`

* Added ``--diffprefs`` option to ``dms2_logoplot``

2.1.0
------
* Added programs and docs for `fracsurvive`.

* Added ``--scalebar`` to ``dms2_logoplot``.

* Add `grouplabel` option and preserve group order for faceted plots by batch programs.

* Handle dependencies without `__version__` attribute

2.0.2
------
* Added ``--sitemask`` option to ``dms2_bcsubamp`` / ``dms2_batch_bcsubamp``.

* Standardized color scheme in ``*_cumulmutcounts.pdf`` plot.

* Ensure naturally sorted average prefs from ``dms2_batch_prefs``.

2.0.1
------
* A few packaging changes for PyPI

2.0.0
--------
This version is a complete re-write of `dms_tools <https://github.com/jbloomlab/dms_tools>`_ version 1.2.2.
