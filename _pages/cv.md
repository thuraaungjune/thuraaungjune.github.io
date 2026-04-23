---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* B.Eng. in Software Engineering, specialized in Artificial Intelligence, King Mongkut's Institute of Technology Ladkrabang, Bangkok, Thailand, July 2023 -- Present

## Research Experience

* AI Research Intern, AI Singapore & VISTEC, Part-time, Singapore, April 2025 -- Present
  * Participating in Southeast Asian LLM research.
  * Translated instruction-following datasets for Burmese LLM evaluation.
  * Built evaluation datasets for seven Burmese NLP tasks.
  * Evaluated Burmese NLP benchmarks for LLMs.

* Machine Learning Engineer, Looloo Technology, Part-time, Bangkok, Thailand, June 2025 -- Dec 2025
  * Finetuned Flow Matching Transformer models for Thai TTS.
  * Finetuned speech-augmented language modeling for Thai language.
  * Created synthetic Thai speech datasets with 25k sentences using Thai TTS.
  * Built evaluation pipelines for Thai TTS systems.

* Lab. Member, Language Understanding Laboratory, Part-time, Remote, June 2022 -- Present
  * Built large-scale Myanmar corpora for OCR and language modeling.
  * Supervised speech corpus creation for the medical domain.
  * Fine-tuned transformer models for sequence and token classification tasks.
  * Reproduced experiments for myNLP, the first Burmese NLP toolkit.

## Achievements

* Full Scholarship: Child's Dream Foundation Scholarship covering tuition, living expenses, and other expenses.
* Hackathon Winner: Season 2 Championship Award (50,000 THB) for the 42 Bangkok x CDG Group Hackathon.
* Best Paper Award: 20th IEEE iSAI-NLP Conference and 10th Anniversary of the Artificial Intelligence Association Thailand.

## Teaching Experience

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications

### Peer-reviewed International Conferences
<ul>{% for post in site.publications reversed %}{% if post.category == 'conferences' %}{% include archive-single-cv.html %}{% endif %}{% endfor %}</ul>

### Journal Articles
<ul>{% for post in site.publications reversed %}{% if post.category == 'manuscripts' %}{% include archive-single-cv.html %}{% endif %}{% endfor %}</ul>

## Skills

* Language Proficiency: Burmese (Native), English (Professional Fluency)
* Programming Languages: Python, Rust, C/C++, Java, JavaScript, SQL, Prolog
* Data Tools: NumPy, Pandas, SciPy
* Developer Tools: Git, Docker, VS Code, AWS SageMaker
* Frameworks and Libraries: PyTorch, TensorFlow, OpenCV, spaCy, NLTK, LangChain, OpenNMT, FastAPI, MLflow
