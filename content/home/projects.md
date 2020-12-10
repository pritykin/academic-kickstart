+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Research"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 5

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""

# [bioRxiv 2020]{{< ref "publication/2020-CD8T/index.md" >}}
# [Nat Biotechnol 2017]{{< ref "publication/2017-nat-biotech-guide-scan/index.md" >}}

+++

We develop computational methods for design and analysis of high-throughput functional genomic assays and perturbations, with a focus on multi-modal single-cell technologies. We apply these methods to study regulatory genomics of cell function and cell-cell interactions *in vivo* in close collaboration with experimental biologists, with a focus on immunology and cancer.

Examples of our past and ongoing work are below.

<br/>


{{< figure library="true" src="cd8t-compile.png" >}}

CD8 T cells form the central component of adaptive immune system and are essential in defense against viral and bacterial infections and in tumor immunity. Better molecular characterization of CD8 T cells in different contexts is fundamentally important and can lead to improved clinical results in cancer immunotherapies, infectious diseases, autoimmunity. We performed an extensive genomic, single-cell, and transcription factor [analysis](publication/2020-cd8t/index.html) of CD8 T cell functional and dysfunctional states. We now continue studying regulatory mechanisms and cell-cell interactions governing CD8 T cell activation and functional commitment across immune challenges using single-cell multi-omics.

<br/>


{{< figure library="true" src="guidescan.png" >}}

Programmable genome editing using CRISPR has tremendously advanced life sciences. To facilitate the use of this technology, especially in the noncoding genome and for batch screens,
we developed [GuideScan](publication/2017-nat-biotech-guide-scan/index.html), a fully customizable CRISPR guide RNA design tool. We now continue working on tools for design and analysis of CRISPR-based genome perturbations and their combinations with single-cell functional genomic assays.

<br/>


{{< figure library="true" src="Tregs-fig1.png" >}}

Regulatory T (Treg) cells are critical for tolerance to self-antigens and preventing autoimmunity. Their differentiation and function are controlled by transcription factor Foxp3, but mechanistic understanding of Foxp3 role remains elusive. Using functional genomic analysis, [we explored](publication/2019-nat-immunol-foxp-1-foxp-3-treg/index.html) Foxp3 function and its interaction with a highly expressed closely related factor Foxp1. We are now studying the role of Foxp3 and other factors in organizing chromatin architecture of Treg cells.

<br/>


{{< figure library="true" src="HEAP-cyrano.png" >}}

Cross-linking immunoprecipitation followed by sequencing (CLIP-seq) is a family of methods for profiling sites of protein binding to RNA. In particular, CLIP has been used to identify targets of microRNAs, small non-coding RNA molecules that, when bound to a protein Ago2, regulate gene expression post-transcriptionally. We developed a new algorithm [CLIPanalyze](https://bitbucket.org/leslielab/clipanalyze) for analysis of such data and used it for [comprehensive analysis](publication/2020-mol-cell-heap/index.html) of microRNA targets *in vivo* in mouse embryonic stem cells, developing embryos, adult tissues and multiple cancer models.
