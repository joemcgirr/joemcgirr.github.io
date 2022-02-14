---

permalink: /fun_projects/
title: "Projects"
excerpt: "Side projects just for fun"

excerpt: ""
author_profile: false

header:
  overlay_image: grandma.jpg
  
feature_row:
  - image_path: coverage.png
    alt: "Variant Filtering and QC"
    title: "Variant Filtering and QC"
    excerpt: "This is a pipeline to generate a filtered SNP .vcf file from raw .fastq files. The approach is designed for hundreds of whole-genome low coverage sequences."
    url: /files/code_tutorials/Pacific_Herring_fastq_to_vcf.html
    btn_label: "See Code"
    btn_class: "btn--inverse"
feature_row2:
  - image_path: fig7.png
    alt: "Overlapping Genomic Regions of Interest"
    title: "Overlapping Genomic Regions of Interest"
    excerpt: "This is a quick tutorial on finding genes near candidate SNPs using my favorite R package plyranges."
    url: /files/code_tutorials/plyranges_tutorial.html
    btn_label: "See Code"
    btn_class: "btn--inverse"
feature_row3:
  - image_path: cam.jpg
    alt: "Building a beginner trad rack"
    title: "Building a beginner trad rack"
    excerpt: "A set of analyses I used to find the perfect combination of rock climbing gear. I collected data for trad equipment offered by several manufacturers and compare price/quality tradeoffs."
    url: /files/code_tutorials/trad_rack.html
    btn_label: "See Code"
    btn_class: "btn--inverse"
feature_row4:
  - image_path: cluster1.png
    title: "Using the FARM Computer Cluster"
    excerpt: "A tutorial on how to submit jobs on the UC Davis FARM cluster. Developed for ECL243 (Ecological Genomics graduate level course)"
    url: /files/code_tutorials/FARM_Tutorial.html
    btn_label: "See Code"
    btn_class: "btn--inverse"
    

  
---




{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}



