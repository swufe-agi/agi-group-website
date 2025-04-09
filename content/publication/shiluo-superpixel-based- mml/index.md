---
title: 'Superpixel-based multi-scale multi-instance learning for hyperspectral image classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shiluo Huang
  - Zheng Liu
  - Wei Jin
  - Ying Mu




# date: '2025/1/25'
doi: 'https://doi.org/10.1016/j.patcog.2024.110257'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.citation
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Pattern Recognition, Volume 149, May 2024, Article 110257*
publication_short: In *Pattern Recognition*

abstract: Superpixels can define meaningful local regions within a hyperspectral image (HSI) and have become the building blocks of various HSI classification methods. The superpixels in HSIs consist of multiple spectral pixels, sharing a similar structure with the data in multi-instance learning (MIL). However, the potential of MIL methods in the field of HSI classification has been rarely explored. In this paper, we propose the superpixel-based multi-scale multi-instance learning (MSMIL) framework, enhancing the superpixel representation with MIL for the first time. Segmenting the HSIs with superpixels, MSMIL converts the HSI classification into MIL problems and extracts superpixel representations via the MIL method, namely multi-instance factor analysis (MIFA). Compared with the existing methods focusing exclusively on the local information, MIFA utilizes the deviations from an overall generative model to describe the superpixels, retaining both the local and the global information. Moreover, MSMIL introduces multi-scale superpixels and a spectral–spatial decision fusion strategy for further refinement, where the results of multi-scale superpixel maps are weighted according to prediction certainty and spatial consistency. The proposed method is evaluated on four benchmark datasets and achieves competitive results. For example, MSMIL outperforms the comparison methods with a margin of 5% overall accuracy on the Indian Pines dataset, when 2% pixels are selected as the training set.
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->


# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [MIL,superpixel,CCF-B]

# # Display this page in the Featured widget?
# featured: true

# # Custom links (uncomment lines below)
# # links:
# # - name: Custom Link
# #   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.2017-01-01T00:00:00Z
# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
