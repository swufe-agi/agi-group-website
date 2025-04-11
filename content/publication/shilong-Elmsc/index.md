---
title: 'Enhanced latent multi-view subspace clustering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Long Shi
  - Lei Cao
  - Jun Wang
  - Badong Chen

# date: '2025/1/25'
doi: '10.1109/TCSVT.2024.3430041'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.citation
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Circuits and Systems for Video Technology, Volume 34, Issue 12, December 2024, Pages 12480–12495, Date of Publication 17 July 2024*
publication_short: In *IEEE TCSVT*

abstract: Latent multi-view subspace clustering has been demonstrated to have desirable clustering performance. However, the original latent representation method vertically concatenates the data matrices from multiple views into a single matrix along the direction of dimensionality to recover the latent representation matrix, which may result in an incomplete information recovery. To fully recover the latent space representation, we in this paper propose an Enhanced Latent Multi-view Subspace Clustering (ELMSC) method. The ELMSC method involves constructing an augmented data matrix that enhances the representation of multi-view data. Specifically, we stack the data matrices from various views into the block-diagonal locations of the augmented matrix to exploit the complementary information. Meanwhile, the non-block-diagonal entries are composed based on the similarity between different views to capture the consistent information. In addition, we enforce a sparse regularization for the non-diagonal blocks of the augmented self-representation matrix to avoid redundant calculations of consistency information. Finally, a novel iterative algorithm based on the framework of Alternating Direction Method of Multipliers (ADMM) is developed to solve the optimization problem for ELMSC. Particularly, we theoretically analyze the convergence of ELMSC in detail. Extensive experiments on real-world datasets show that our proposed ELMSC is able to achieve higher clustering performance than some state-of-art multi-view clustering methods. Moreover, our experiments show that our method remains effective with randomly chosen parameters, demonstrating ELMSC’s practical potential.
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->


# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [CCF-B,IEEE]

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
