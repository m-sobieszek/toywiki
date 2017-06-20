Overview
--------

NOTE: Without any precedence to borrow from, this project (including these contribution guidelines) is highly experimental.

Contributions can be:

1.  [Issues](https://github.com/ycpei/toywiki/issues):
    1.  discussions on open problems
    2.  comments on existing articles: typos, mistakes, wrong / missing attributions, article structures, etc
    3.  questions on existing articles
2.  [Pull requests](https://github.com/ycpei/toywiki/pulls):
    1.  The edited version of an existing article after your review
    2.  A new article

Issues
------

Regarding issues, unfortunately Github does not support maths natively in their Markdown system. See <https://github.com/github/markup/issues/897> . It is therefore suggested that issue posts are written in Markdown with maths in latex inline code or code blocks. You can test your post on [stackedit](https://stackedit.io/editor) before wrapping the latex in code.

Pull requests
-------------

Please follow these guidelines on pull requests:

1.  Before you invest time on a nontrivial pull request making substantial changes, it is preferable to open an issue stating what changes you want to see.
2.  Any new article in a pull request should be related to at least one of the existing articles manifested by hyperlinks.
3.  Commit messages should be written as clearly as possible.
4.  In any article, attributions should be given if there are relatively new results that are not original.
5.  There is no specific style guideline at this stage. But notes should be written in a simple and clear way.
6.  The file(s) changed in a pull request should be Vimwiki (`.wiki`) file(s) in `wiki/` directory, as well as `config/tw.bib` in case of bibliography changes. Vimwiki is a lightweight markup language and a Vim plugin. See <https://github.com/vimwiki/vimwiki> for usage. And the beginning of a `.wiki` file should look like:

        %title Title of article
        %date Date of last change to this file

        :tag1:tag2:tag3:

7.  Theorems should have a `Theorem` in boldface at the beginning of a line, followed by a dot, followed by the content of the theorem. Same goes for Claims, Corollaries etc.
8.  Proofs should have a `Proof` in boldface at the beginning of a line, followed by a dot, followed by the content of the proof, followed by a QED symbol `$\square$`.
9.  Labels for theorems, equations etc. are optional and should be done manually.
