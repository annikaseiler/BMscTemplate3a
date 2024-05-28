# References

In this README, you can find some tips and tricks for handling the references.

## Formatting

- Make sure to add the starting page of the reference in case it is of type 'article' (journal publication).Optionally, you can also add the last page and this is indeed the default for many references from Inspire. However, we would recommend to always remove the last page because it can be tedious to find the last page if it is not given in Inspire. An example of this can be found in the entry `ATLAS:2012yve` in `bib/experimental.bib`, where `pages = "1--29",` was replaced by `pages = "1",`.
- By default, the month is added to the year if present. We recommend to suppress this by `x-ing` the 'month' field as also recommended for the pages.
- For theses, make sure that the full name of the institution is given. For example, the bibtex entry from https://inspirehep.net/literature/1775688 (thesis of Marcel Rieger) includes `school = "RWTH Aachen U.",`, which should be changed to `school = "RWTH Aachen University",`.
- There are also unpublished CMS and ATLAS "notes", meaning CONF or PAS or similar documents that are public and have undergone collaboration-internal review, but are not published as journal articles. Please always check if there is actually a follow-up journal article that supersedes the unpublished note. If there is none, then you can cite this "note" with the `techreport` type. An example is given with `CMS-PAS-SMP-22-009`. Please add the `reportNumber` and the `url` to the entry on cds (CERN Document Server).