Dialoa
======

Dialoa (Dialectica's Open Access team) develops a framework 
to produce high-quality Open Access journals 
using a markdown- and [Pandoc](https://pandoc.org/) based workflow.

The Dialoa publishing framework
-------------------------------

The framework is designed to produce professional-quality
outputs (PDFs, epubs, ...) at a low cost. Our goal is to enable
small teams of academics with little prior technical knwoledge
and a tight budget to produce beautiful PDFs and webpages.

The complete framework is still under development but will 
be made available here when mature. 

Dialoa publishing tools
-----------------------

We're publishing here framework components that can be reused
independently. 

* Documentation: an Open Manual of Markdown Style for 
  copyeditors that doesn't require
  technical knowledge of markdown, LaTeX, the command line etc.
* Production tools, such as:
  * pandoc filters to handle columns, statements (theorems), etc.
  * a highly flexible template for advanced LaTeX output (pandokoma)
* Development tools:
  * `docker-ojs-dev` dockerized Open Journal Systems for plugin 
    development.
  * `luabuilder`: to write large Pandoc lua filters from multiple
    files.

What is deposited here is currently used in the production
process of journal, [Dialectica](https://dialectica.philsoophie.ch).
This means that they've reached at least a satisfactory level
of functionality, notably for PDF outputs.

Tools with __releases__ are mature enough for long-term use.

Have a look around! 

## Membership

Issues and PRs welcome. Get in touch if you'd like to join the organization.

## Credits

Dialoa is a project of the association [philosophie.ch](https://philosophie.ch)
developed for the academic journal [Dialectica](https://dialectica.philsoophie.ch).
