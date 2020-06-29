---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Extracting Conflict Networks from the News with Semantic Hypergraphs "
event: "Sunbelt 2020"
event_url: http://www.pfeffer.at/sunbelt/
location: "Virtual"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "We recently introduced a formal language and knowledge representationmodel that we call /"semantic hypergraph/" (arXiv:1908.10784) and that aims at providing explicit structure and reducing ambiguity as much as possible in natural language. We take advantage of modern NLP tools, such as part-of-speech tagging, dependency parsing and co-reference resolution to transform free text into semantic hypergraphs, where units of speech (typically sentences) are represented as recursive ordered hyperedges. This bears advantages over conventional approaches such as semantic graphs, including the ability to build new concepts from existing ones, to organize statements into regular structures of predicates followed by an arbitrary number of entities, and to represent statements about other statements, at an arbitrary level of nesting. Of particular interest to this conference session, this representation facilitates the discovery of views of perspectives that summarize and aggregate a certain aspect of what is contained in the text, but that is potentially spread across a large corpus, possibly implicitly, and in an entangled fashion. Our contribution demonstrates the extraction of networks of conflicts between actors from large corpora of news headers. We consider two sets of news headers, collected from Reddit -- a popular social news aggregator and discussion forum. One set is extracted from the /"worldnews/" subreddit (dedicated to global news in English), the other from /"politics/" (dedicated to U.S. politics). They both cover the time period from Jan 1st, 2013 to Aug 1st, 2017 and consist of approximately 4 million headlines. We show how we use the semantic hypergraph model to identify actors as well as conflict relationships in the context of some topic. Furthermore, co-references (such as /"President Obama/", /"Barack Obama/") and some actor types (e.g., /"female/", /"male/", /"non-human/", /"group/") are automatically inferred. This higher-order inferred knowledge can then be used to generate both ego-centered conflict networks and contextual conflict networks (summarizing the network of conflicts surrounding a given topic). We automatically build, for example, the conflict network surrounding the topic of /"Syria/" in English-speaking world news. In this case, we use a simple alliance detection algorithm to show that the factions expressed in this conflict correspond convincingly to actors (countries, politicians and others) aligned with NATO on one side, and Russia/China on the other. More broadly, our contribution aims to advance the state-of-the art in text understanding for social and semantic network analysis by going beyond bag-of-word approaches and conventional topic models."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-07-20T20:00:00+00:00
# date_end: 2019-11-24T19:56:00+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-06-28T19:30:00+00:00

authors: ["Telmo Menezes", "Camille Roth"]
tags: ["Computational Social Science", "NLP"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
