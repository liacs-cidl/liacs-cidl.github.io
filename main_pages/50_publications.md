---
layout: page
title: Publications
permalink: publications/
include_in_menu: true
---

<!-- See https://github.com/pcooksey/bibtex-js/wiki for formatting -->

<script type="text/javascript" src="/js/bibtex_js.min.js"></script>

<bibtex src="/assets/publications/publications.bib"></bibtex>

<div class="bibtex_structure">
<div class="group year" extra="DESC number">
  <div class="templates"></div>
</div>
</div>

<div class="bibtex_template">
<table>
    <td style="vertical-align:top;">
    -</td><td>
    <span class="author" max="5">
        <span class="von"></span> 
        <span class="last"></span>
        <span class="junior">, </span>
        <span class="first_initial">, </span>
    </span>
    <span class="if year">, (<span class="year"></span>)</span>.
    <span class="title"></span>. 
    <span class="if journal">
        <i>
            <span class="journal"></span>
        </i>
    </span>
    <span class="if booktitle">In 
        <i>
            <span class="booktitle"></span>
        </i>
    </span><span class="if eprint">
        <i>
            <span class="if archivePrefix">
                <span class="archiveprefix"></span>:
            </span>
            <span class="eprint"></span>
        </i>
    </span>
    <span class="if volume">
    <i>, <span class="volume"></span>
    </i>
    </span>
    <span class="if number">(<span class="number"></span>)</span>
    <span class="if pages">, <span class="pages"></span></span>
    <span class="if journal || booktitle || eprint">.</span>
    <span class="if pdf_url">[<a class="pdf_url">PDF</a>]</span>
    <span class="if project_url">[<a class="project_url">Project</a>]</span>
    
    </td>
</table>
</div>

<div id="bibtex_display"></div>
