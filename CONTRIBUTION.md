Overview {#Overview}
--------

NOTE: Without any precedence to borrow from, this project (including
these contribution guidelines) is experimental.

Contributions can be:

1.  [Issues](https://github.com/ycpei/toywiki/issues):
    1.  discussions on open problems
    2.  comments on existing articles: typos, mistakes, wrong / missing
        attributions, article structures, etc
    3.  questions on existing articles
2.  [Pull requests](https://github.com/ycpei/toywiki/pulls):
    1.  The edited version of an existing article after your review
    2.  A new article

Issues {#Issues}
------

### open problems {#open problems}

In general a problem may be in one of three status in a universal sense:

1.  Open. No one on Earth has a complete solution to it.
2.  Folklore. It is believed to have been solved by some, but not
    complete solution has been published.
3.  Solved. A complete solution has been published.

But these universal statuses are not useful, because in everyday life, a
problem can only be either open or solved from a person\'s perspective,
and unless one is omniscient, a problem open to them may fall into any
one of the three categories above. They may not be aware of the
solution, or that they have read the solution but there are gaps between
their mathematical background and that assumed by the solution. For
example, a usual problem posted on stack exchange is open to the poster
until they understand a solution.

It is open problems in this sense we work on in toywiki. They can be
posted on the issue page for discussion, with the tag `open-problem`. If
it is open due to ignorance about the literature, then a pointer to the
solution should resolve the issue. Otherwise once they are solved, it is
high time to record the solution in the wiki.

### math equation rendering {#math equation rendering}

Unfortunately Github does not support maths natively in their Markdown
system. See <https://github.com/github/markup/issues/897> . It is
therefore suggested that issue posts are written in Markdown with maths
in latex inline code or code blocks. You can test your post on
[stackedit](https://stackedit.io/editor) before wrapping the latex in
code.

Pull requests {#Pull requests}
-------------

Please follow these guidelines on pull requests:

1.  Before you invest time on a nontrivial pull request making
    substantial changes, it is preferable to open an issue stating what
    changes you want to see.
2.  Any new article in a pull request should be related to at least one
    of the existing articles manifested by hyperlinks.
3.  Commit messages should be written as clearly as possible.
4.  In any article, attributions should be given if there are relatively
    new results that are not original.
5.  There is no specific style guideline at this stage. But notes should
    be written in a simple and clear way.
6.  The file(s) changed in a pull request should be Vimwiki (`.wiki`)
    file(s) in `wiki/` directory, as well as `config/tw.bib` in case of
    bibliography changes. Vimwiki is a lightweight markup language and a
    Vim plugin. See <https://github.com/vimwiki/vimwiki> for usage. And
    the beginning of a `.wiki` file should look like:

        %title Title of article
        %date Date of last change to this file

        :tag1:tag2:tag3:

7.  Theorems should have a `Theorem` in boldface at the beginning of a
    line, followed by a dot, followed by the content of the theorem.
    Same goes for Claims, Corollaries etc.
8.  Proofs should have a `Proof` in boldface at the beginning of a line,
    followed by a dot, followed by the content of the proof, followed by
    a QED symbol `$\square$`.
9.  Labels for theorems, equations etc. are optional and should be done
    manually.
