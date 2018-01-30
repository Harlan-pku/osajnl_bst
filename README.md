# osajnl_bst
A modified bibliographystyle file for OSA journals.

# Changes from original files

* The edition information should follow the title closely, instead of in the end.
* The two words in an edition information should not be break into different lines, e.g. ``2nd~ed.`` is preferred.
* Support to ``articleno`` field is added.
* The issue information of a journal is correctly added. (only in ``osajnl.bst``)
* For ``chapter in a book`` type reference, the book title is corrected to *emphasize*.

# Short guideline

* For conference paper in SPIE proceedings, a ``journal`` type with journal name of ``Proc. SPIE`` is preferred.

```
@article{spie_example,
    title = {the title},
    volume = {the number of the SPIE proceedings},
    journal = {Proc. SPIE},
    author = {the authors},
    year = {2016},
    pages = {conference paper ID, e.g. 987608}
}
```

* For conference paper in IEEE or OSA proceedings, the publisher field should be filled correctly.