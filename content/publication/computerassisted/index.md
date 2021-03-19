---
title: "Computer Assisted Composition with Recurrent Neural Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Dongwoo Kim


date: "2017-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract:

# Summary. An optional shortened abstract.
summary: While it is fun to generate music using machine learning, it might be more even fun if we had some control over the results. As a simple starting point, rather than allowing the algorithm to choose all the notes, played with partially specify a piece of music. We give a taste of what can be done in this space. <br> <br> We started with a piece by Mozart from the MuseData corpus. With this track and a previously trained model as our starting point, we  <br><br> **1.** Chose a single voice (or midi track) to use as our guideline. You can hear this voice in isolation in the first track of the playlist below. <br> **2.** Fixed the rhythmic (or timing) information of the remaining three tracks to be the same as that of the original midi file. <br> **3.** Sampled the pitches of the remaining tracks condiitonal on the above information. Two such samples are included here. In these samples, the original Mozart line has the timbre of a grand piano, while the remaining (computer generated) lines have the timbre of a synthesised guitar. One sample is generated using conditional sampling, the other conditional probability maximisation (leading to two different characters of result as discussed in the paper).<br><br>The accompaniments are clearly responding to the fixed line from Mozart. It is sobering to compare the results with the sparkling playfulness of the original composition, however. The final track in the playlist demonstrates this, with the same instrument patches (timbres) as before, applied to the original notes of the input midi file.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Audio Samples on Soundcloud
  url: https://soundcloud.com/user-920800058/sets/mozart-k160-human-computer
url_pdf: 'https://arxiv.org/abs/1909.05030'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Publication name and optional abbreviated publication name.
publication_short: ACML


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- rl

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
