# UC Davis Linear Algebra Laboratory Coursework Website
Welcome to Jonathan Trans's UC Davis Linear Algebra Laboratory Coursework Website. \
We are excited to see you here! 😊 

I am currently working under UC Davis Professor Ali A. Dad-del. We are restructuring the MAT22AL (Linear Algebra Computer Laboratory) coursework website through front-end development tools including: PreTexT, XML, LaTex, HTML, CSS, and Python. The new website is polished with a pleasurable user interface, alongside with new multitasking options that will eventually be able to connect via UC Davis lab username and sign-in options. Throughout this process, I built web applications in an agile and iterative way using agile methodologies and Git/Github as a full stack developer. 

Tools: HTML, CSS, Git/Github, Python, PreText, XML, and LaTeX 👻

# Link(s) : 
LinkedIn: https://www.linkedin.com/in/jonathantrans/ \
Personal Website: https://jonathantrans.github.io/ \
Project Website: TBA

The PreTeXt Guide 😎
=================

PDF and HTML versions of this guide are available at the [PreTeXt](https://pretextbook.org) site in the Documentation area.

If you wish to build from source, possibly as part of contributing improvements, follow these steps:

1.  To build LaTeX for input to `pdflatex`:
        cd /path/to/mathbook
        xsltproc -xinclude -o guide.tex xsl/pretext-latex.xsl doc/guide/guide.xml
1.  And for HTML output:
        cd /path/to/mathbook
        xsltproc -xinclude xsl/pretext-html.xsl doc/guide/guide.xml
1.  You might prefer to set your default directory to someplace outside the PreTeXt distribution and include full paths to the XSL and XML files in the `xsltproc` command, so your output is not mixed in with your source.
1.  Note, we do not include directions here for the multiple steps necessary to have the WeBWorK examples built correctly.  You will get an error message, but the rest of your ouput should not be affected.

If you are contributing new material, note that there are three important elements in use.  Please make use of them in your contribution.
* `tag` - for element names
* `tage` - for names of empty elements
* `attribute` - for names of attributes
