---
layout: page_software
title: "PFASST++"
date: 2014-06-15 16:45 +0200
updated: 2016-02-12 10:00:00 +0200
navbar: Software
logo: 
code_url: https://github.com/Parallel-in-Time/PFASST
language: C++
github_repo: "Parallel-in-Time/PFASST"
license: BSD 2-clause
institutes:
  - jsc
topics:
  - numerics
  - resilience
releases:
  - version: 0.5.0
    date: 2015-06-01
    link: https://github.com/Parallel-in-Time/PFASST/releases/tag/v0.5.0
    download: https://github.com/Parallel-in-Time/PFASST/archive/v0.5.0.zip
  - version: 0.4.0
    date: 2015-04-17
    link: https://github.com/Parallel-in-Time/PFASST/releases/tag/v0.4.0
    download: https://github.com/Parallel-in-Time/PFASST/archive/v0.4.0.zip
  - version: 0.3.0
    date: 2014-12-12
    link: https://github.com/Parallel-in-Time/PFASST/releases/tag/v0.3.0
    download: https://github.com/Parallel-in-Time/PFASST/archive/v0.3.0.zip
  - version: 0.2.0
    date: 2014-08-30
    link: https://github.com/Parallel-in-Time/PFASST/releases/tag/v0.2.0
    download: https://github.com/Parallel-in-Time/PFASST/archive/v0.2.0.zip
  - version: 0.1.0
    date: 2014-07-26
    link: https://github.com/Parallel-in-Time/PFASST/releases/tag/v0.1.0
    download: https://github.com/Parallel-in-Time/PFASST/archive/v0.1.0.zip
developers:
  - name: Matthew Emmett
    email: matthew@emmett.ca
    lead_developer: true
  - name: Torbjörn Klatt
    email: t.klatt@fz-juelich.de
    lead_developer: true
  - name: Robert Speck
    email: r.speck@fz-juelich.de
  - name: Daniel Ruprecht
    email: daniel.ruprecht@usi.ch
  - name: Fabian Köhler
  - name: Selman Terzi
short_desc: A C++ library for SDC, MLSDC and PFASST.
---
{% raw %}
<div class="alert alert-info">
  This page is a demonstration on how a description page for a software can look like.
  PFASST++ is not part of JLESC.
</div>
{% endraw %}

A modern C++ library for the PFASST algorithm. 

The PFASST project is a C++ implementation of the parallel full approximation 
scheme in space and time (PFASST {% cite EmmettMinion2012 --file external/pfasst_software.bib%})
algorithm, which in turn is a time-parallel algorithm for solving ODEs and PDEs.
It also contains basic implementations of the spectral deferred correction (SDC) 
and multi-level spectral deferred correction (MLSDC) algorithms.

{% bibliography --cited --file external/pfasst_software.bib %}
