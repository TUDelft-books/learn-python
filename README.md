
# Python for Engineers

<img src="https://raw.githubusercontent.com/TUDelft-CITG/learn-python/main/book/figures/learn-python-logo.png" width=80 style="float: right;"/>

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16753127.svg)](https://doi.org/10.5281/zenodo.16753127)
[![Jupyter Book Badge](https://raw.githubusercontent.com/executablebooks/jupyter-book/47e06598ef05bd429467a7de66a7fb3a83e89c2f/docs/images/badge.svg)](https://jupyterbook.org) 
[![Jupyter lite Badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://github.com/jupyterlite)

Python for Engineers is an interactive online textbook (website) that functions as a self-paced online course. It is meant to provide (and refresh) knowledge of the Python Programming language. The most recent version of the book can be found at https://oit.tudelft.nl/learn-python.

The course was originally developed for students in the fields of: Civil Engineering, Environmental Engineering, Applied Earth Sciences and Construction Management and Engineering. These programs are part of the faculty of Civil Engineering and Geosciences at Delft University of Technology in the Netherlands. We try to draw on examples from these fields, but the course contents should be relevant for any engineering or applied geoscience discipline.

This book draws heavily on the content of ["Think Python 2nd Edition" by Allen B. Downey](https://greenteapress.com/wp/think-python-2e/), which is generously provided with a CC BY NC 3.0 Unported license, allowing us to create this Python resource that is customized for our own students. See the [Credits page](https://oit.tudelft.nl/learn-python/credits) of the book for complete information on licenses and shared resources.

## Course Overview

The course aims to provide freshman master students with essential Python programming skills tailored to their field of study. By the end of the course, students will:

1. Gain a solid foundation in Python programming.
2. Understand how Python can be applied in engineering and geoscience.
3. Develop the ability to automate tasks and analyze complex data using Python.
4. Acquire skills to visualize information effectively.
5. Learn to develop efficient algorithms for problem-solving in their domain.
6. Enhance their academic performance and future professional prospects.
7. Become part of a vibrant learning community and foster collaboration with fellow classmates.

Visit the [book introduction page](https://tudelft-citg.github.io/learn-python/) for more information.

## Acknowledgments

Financial support for this project was provided through an open education grant from the Educational Management Team for the Civil Engineering and Geosciences Faculty at Delft. The content was first developed for Summer 2022 by Sandra Verhagen and a team of TA's in Jupyter notebooks that were auto-graded in Vocareum (Guilherme Ferreira Sêco de Alvarenga, Arsenijs Nitijevskis and Jarno Vegting). For Summer 2023 a second round of funding was optained to update the content and adapt it to an entirely open and self-paced course without enrollement via a Jupyter Book, led by Robert Lanzafame. Special thanks goes to Miguel Mendoza Lugo who adapted the notebooks into the Jupyter Book format and implemented the interactive features, as well as Ahmed Farahat, who helped create the fun new visual features that make understanding the material easier in the Jupyter Book platform, as well as the In a Nutshell summaries. Guilherme Ferreira Sêco de Alvarenga made improvements to the content and set up the interactive Python feature via [TeachBooks](teachbooks.io) tools. In late 2024 and 2025, Shiya Tang improved the contents and converted exercises from JupyterQuiz to H5p. Tom van Woudenberg helped with a number of TeachBooks features, adding content such as Sympy and for being a fantastic teacher-collaborator for devising interesting ways for using online books in educational contexts.

This Book is maintained and developed by staff of the Faculty of Civil Engineering and Geosciences of TU Delft, the Netherlands. If you have questions or suggestions, get in touch via a GitHub Issue or by email at MUDE-CEG@tudelft.nl. Contributions and feedback are very much welcomed via either of these channels!

## Technical Details

This book is created using open source tools: it is a Jupyter Book that uses a number of features from [TeachBooks](https://teachbooks.io/) and is written using Markdown, Jupyter notebooks and Python files to generate some figures. See the Credits page for additional information.

Starting with the 2025-26 academic year, the book uses semantic versioning of form `vA.B.C`, where `A` is the major version as an academic year (e.g., 2025), `B` is the minor version and `C` is the patch version. The major version updates will not necessarily occur every year; for example, in 2027 we may still be on version `v2025.7.x`.

Also beginning with the 2025-26 academic year, the TeachBooks Deploy Book Workflow is used to redirect users to the major version of the book in use, with branches being named accordingly (e.g., `2024` and `2025`). When a new major version is released, the default branch in GitHub should also be updated, reflecting the current major version.

### Updating the Book

The primary mechanism for updating the book is by making a new GitHub Release. In addition to changes in content, care should be taken to make sure text (metadata, instruction, etc) in relevant files remains up to date, specifically: README, Credits and Intro pages and CITATION.cff. These files each contain several sentences and paragraphs that are copy/pasted manually and should remain in sync.

Once content changes are made, do the following:

1. Determine what the next version number is. Major updates should be rare (maximum once per academic year); minor updates should correspond to new pages, exercises, etc., whereas patches should fix typos or other small changes that do not affect the technical contents of the book.
1. Document the changes clearly in a draft release note. If no changes to the book contents are made, write, e.g.: _This release makes no changes to the technical contents of the book._
1. Add notes to readers about minor changes on the relevant pages of the book (see TeachBooks Manual for suggestions).
1. Check the metadata files listed above and make any necessary changes, noting: a) the CITATION.cff file only needs to be updated in case of additional authors being added, and b) the recommended citation on the Credits page only needs to be updated when the major version is updated.
1. Publish release.
1. Check that version number was updated properly on Zenodo.

If a major update is made, a new branch must be made with the appropriate year number and made into the default branch, redirect should be updated using the Deploy Book Workflow settings and a banner should be used on older versions of the book to notify readers. A banner can also be used temporarily to notify readers how to find the older version. Be sure to update the year number metadata in the relevant files listed above.

 <img src="https://raw.githubusercontent.com/TUDelft-CITG/learn-python/mike/book/figures/TUDelft_logo_cmyk.png" width=170  style="float: right;"/> 

