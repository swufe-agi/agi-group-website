---
title: 'LinkBreaker: Breaking the Backdoor-Trigger Link in DNNs via Neurons Consistency Check'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhenzhu Chen
  - Shang Wang
  - Anmin Fu
  - Yansong Gao
  - Shui Yu
  - Robert H. Deng



# date: '2025/1/25'
doi: '10.1109/TIFS.2022.3175616'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.citation
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Information Forensics and Security (Volume 17, Pages 2000–2014, Date of Publication 16 May 2022)*
publication_short: In *IEEE TIFS*

abstract: Backdoor attacks cause model misbehaving by first implanting backdoors in deep neural networks (DNNs) during training and then activating the backdoor via samples with triggers during inference. The compromised models could pose serious security risks to artificial intelligence systems, such as misidentifying ‘stop’ traffic sign into ‘80km/h’. In this paper, we investigate the connection characteristic between the backdoor and the trigger in DNNs and observe the fact that the backdoor is implanted via establishing a link between a cluster of neurons, representing the backdoor, and the triggers. Based on this observation, we design LinkBreaker, a new generic scheme for defending against backdoor attacks. In particular, LinkBreaker deploys a neuron consistency check mechanism for identifying compromised neuron set related to the trigger. Then, the LinkBreaker regulates the model to make predictions based on benign neuron set only and thus breaks the link between the backdoor and the trigger. Compared to previous defenses, LinkBreaker offers a more general backdoor countermeasure that is not only effective against input-agnostic backdoors but also source-specific backdoors, which the later can not be defeated by majority of state-of-the-arts. Besides, LinkBreaker is robust against adversarial examples, which, to a large extent, provides a holistic defense against adversarial example attacks on DNNs, while almost all current backdoor defenses do not have such consideration and capability. Extensive experimental evaluations on real datasets demonstrate that LinkBreaker is with high efficacy of suppressing trigger inputs while incurring no noticeable accuracy deterioration on benign inputs.
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->


# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [CCF-A,IEEE]

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
