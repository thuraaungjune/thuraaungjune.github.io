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

* Visiting Scholar (Summer Research Intern), National University of Singapore, Singapore, May 2026 -- July 2026
  * Developed DIVA (Diversity-Informed Visual Active Learning), an active learning framework for generative Vision-Language Models (VLMs) that combines model uncertainty filtering with visual diversity clustering on final-layer hidden states.
  * Applied DIVA to low-resource cursive OCR for historical Jawi script, addressing language bias toward Arabic, visual degradation, and data inefficiency in VLM fine-tuning.
  * Benchmarked DIVA against existing active learning methods on historical Jawi document line datasets.
  * Achieved a Character Error Rate (CER) of 10.5% on degraded images using only 50% of labeled data, versus 275.6% for random active selection.
  * Conducted research under the supervision of Assoc. Prof. Dr. Min-Yen Kan and PhD candidate Tongyao Zhu.

* Machine Learning Engineer, Looloo Technology, Part-time, Bangkok, Thailand, June 2025 -- Present
  * Finetuned Flow Matching Transformer models for Thai TTS.
  * Finetuned speech-augmented language modeling for Thai language.
  * Created synthetic Thai speech datasets with 25k sentences using Thai TTS.
  * Built evaluation pipelines for Thai TTS systems.
  * Conduted contrastive decoding experiments for the Qwen3-ASR model on Thai language speech recognition.

* Lab. Member, Language Understanding Laboratory, Part-time, Remote, June 2022 -- Present
  * Built large-scale Myanmar corpora for OCR and language modeling.
  * Supervised speech corpus creation for the medical domain.
  * Fine-tuned transformer models for sequence and token classification tasks.
  * Reproduced experiments for myNLP, the first Burmese NLP toolkit.

* AI Research Intern, AI Singapore & VISTEC, Part-time, Singapore, April 2025 -- April 2026
  * Participating in Southeast Asian LLM research.
  * Translated instruction-following datasets for Burmese LLM evaluation.
  * Built evaluation datasets for seven Burmese NLP tasks.
  * Evaluated Burmese NLP benchmarks for LLMs.

## Achievements

* Full Scholarship: Child's Dream Foundation Scholarship covering tuition, living expenses, and other expenses.
* Hackathon Winner: Season 2 Championship Award (50,000 THB) for the 42 Bangkok x CDG Group Hackathon.
* Best Paper Award: 20th IEEE iSAI-NLP Conference and 10th Anniversary of the Artificial Intelligence Association Thailand.
* Summer Research Internship: Awarded by NUS SoC with monthly stipend of 2,000 SGD for summer research visit.
* KMITL Abroad Study Scholarship: Awarded by KMITL SIIE for intern visit to NUS.

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
