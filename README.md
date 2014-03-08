<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. The problem</a></li>
<li><a href="#sec-2">2. Requirements</a></li>
<li><a href="#sec-3">3. Other requirements</a></li>
<li><a href="#sec-4">4. Theorems</a></li>
<li><a href="#sec-5">5. Resources</a>
<ul>
<li><a href="#sec-5-1">5.1. In blogs</a></li>
<li><a href="#sec-5-2">5.2. blogs in org</a></li>
<li><a href="#sec-5-3">5.3. github</a></li>
</ul>
</li>
<li><a href="#sec-6">6. References</a>
<ul>
<li><a href="#sec-6-1">6.1. To the equation</a></li>
</ul>
</li>
</ul>
</div>
</div>



# The problem

I want to have a format that I can convert to `pdf, html`, and maybe
`odt`. The formats I know well are
-   LaTeX
-   org

One thing I like about org is that it is rather simple, and the
documents look clean. I do not like that it seems to change
constantly and that it is not as universally known as LaTeX.

# Requirements

I want to use:
-   links, say [Google](http://google.com).
-   images, say
    
    ![img](./clock.png "A test image")
    
    Apparently one has to have a blank line so that the image looks
    OK. Also, with a caption, the image is centered both in LaTeX and
    HTML export.

# Other requirements

-   code, say
    
        def test(a):
            """This is just a test
        
            Arguments:
            - `a`: test argument
            """
-   math symbols, say \(a^{2}+b^{2}=c^{2}\)
-   displayed equations, like:
    
    \begin{equation}
    a^{2}+b^{2}=c^{2}
    \end{equation}

# Theorems

-   theorems, definitions, etc.
    
    <div class="theorem">
    There are infinite prime numbers \(p\).
    
    </div>

-   references, to a bibliographic resource or to another theorem
    previously stated.
-   tables, say:
    
    <table id="the-table" border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
    <caption class="t-above"><span class="table-number">Table 1:</span> This is a test table</caption>
    
    <colgroup>
    <col  class="left" />
    
    <col  class="left" />
    
    <col  class="left" />
    </colgroup>
    <thead>
    <tr>
    <th scope="col" class="left">a</th>
    <th scope="col" class="left">b</th>
    <th scope="col" class="left">c</th>
    </tr>
    </thead>
    
    <tbody>
    <tr>
    <td class="left">x</td>
    <td class="left">y</td>
    <td class="left">z</td>
    </tr>
    </tbody>
    </table>

# Resources

## In blogs

-   [Makefiles for tikz sagemath and teaching notes written in markdown](http://drvinceknight.blogspot.mx/2013/04/makefiles-for-tikz-sagemath-and.html)
    Dr. Knight shows a workflow having markdown as source format. Also
    uses `sage` for producing images.

-   [org-exp-bibtex | Sail Home](http://bowenli37.wordpress.com/tag/org-exp-bibtex/) A post describing the use of
    `org-exp-bibtex`, which has been removed from org-mode, as seen in:
    [org-exp-bibtex missing in git?](http://thread.gmane.org/gmane.emacs.orgmode/67488/focus%3D67839) From that thread, this post by Eric
    Fraga seems to be useful: [org-exp-bibtex missing in git?](http://thread.gmane.org/gmane.emacs.orgmode/67488/focus%3D67839) as this by
    Rasmus: [org-exp-bibtex missing in git?](http://thread.gmane.org/gmane.emacs.orgmode/67488/focus%3D67839) BTW, this might be the
    origin of all the code using bibtex in org: [dealing with a bibliography](http://article.gmane.org/gmane.emacs.orgmode/2406/match%3Dbibliography)
-   Eric's suggestion apparently uses `ebib`: [joostkremers/ebib · GitHub](https://github.com/joostkremers/ebib)

-   About pandoc: [Pandoc Converts All Your (Text) Documents -
    ProfHacker](http://chronicle.com/blogs/profhacker/pandoc-converts-all-your-text-documents) and [Make Your Own E-Books with Pandoc - ProfHacker](http://chronicle.com/blogs/profhacker/make-your-own-e-books-with-pandoc)

## blogs in org

-   [Org Blogs and Wikis](http://orgmode.org/worg/org-blog-wiki.html)
-   Publishing in info: <org#Publishing>
-   A thread in the mailing list: [Org-Mode for GNU Emacs](http://comments.gmane.org/gmane.emacs.orgmode/45360)
-   A question: [How to create a personal wiki+blog on github using org-mode?](http://stackoverflow.com/questions/8025703/how-to-create-a-personal-wikiblog-on-github-using-org-mode)
-   [renard/o-blog · GitHub](https://github.com/renard/o-blog), the page: [Quick start Guide](http://renard.github.io/o-blog/)
-   More on blogging from org: [Scott Jaderholm: Blogging With Org-mode and Octopress](http://jaderholm.com/blog/blogging-with-org-mode-and-octopress)
-   [Introducing Octopress Blogging for Org-Mode - On Programming](http://blog.paphus.com/blog/2012/08/01/introducing-octopress-blogging-for-org-mode/), the
    repo: [craftkiller/orgmode-octopress · GitHub](https://github.com/craftkiller/orgmode-octopress)

## github

-   [Which is a good format to make documents?](http://rvf0068.github.io/org-document-test/) The github page of this document&#x2026;

# References

## To the equation

We reference equation 1 and table 1 and Theorem 1
