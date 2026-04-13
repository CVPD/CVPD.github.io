---
title: Drift detection on feature attributions for monitoring visual reinforcement
  learning models in maritime port surveillance
authors:
- Francisco Javier Iriarte
- Beatrice Azoubel
- Adrián Carrizo-Pérez
- Andrés Chica Linares
- Luis Unzueta
- Ignacio Arganda-Carreras
date: '2026-01-01'
publishDate: '2026-04-13T10:15:13.091303Z'
publication_types:
- article-journal
publication: '*Open Research Europe*'
doi: 10.12688/openreseurope.22116.1
abstract: Background. Maritime activity is expanding globally, increasing the demand
  for robust port security systems capable of detecting illegal trafficking. Due to
  the growing sophistication of smuggling methods, law enforcement agencies require
  advanced surveillance and prevention technologies such as those developed in the
  SMAUG project. In this context, initiatives such as the SMAUG project aim to deliver
  integrated surveillance capabilities coordinated by a high-level deep reinforcement
  learning (DRL) decision-making system that operates on image-based environmental
  representations. Despite their effectiveness, DRL models are closed-boxes, complicating
  continuous model monitoring (CMM). Conventional drift detection captures shifts
  in input or output distributions yet often fails to explain underlying problems.
  Explainable AI (XAI) techniques can provide a complementary approach with insights
  into the agent's inner workings, enabling monitoring of the concept rather than
  just the data. Methods. We propose FADMON, an XAI-driven concept drift detection
  method for image-based models. FADMON performs statistical drift tests on feature
  attributions to detect deviations in learned policies. We demonstrate how FADMON
  can enhance CMM with a three-stage model monitoring architecture that enables semi-supervised
  explainable model monitoring. We validate our approach with SMAUG's decision-making
  DRL model on a simulated maritime port surveillance environment under multiple unforeseen
  scenarios. Results. FADMON consistently flags drift on all drifted scenarios with
  mean p-values of 0.000 with no variance trough 30 repetitions, with lower mean p-values
  (0.553±0.215) on non-drifted scenarios with respect to other established drift detection
  methodologies such as prior probability shift detection (0.65 ± 0.000), though well
  above the standard 0.05 threshold. Conclusions. FADMON can add an explainability
  layer to the monitoring system while also supporting detection of changes in the
  underlying interpretation of the input data by the model, monitoring the concept
  rather than the data, while matching established drift detection methods metrics-wise.
links:
- name: URL
  url: https://open-research-europe.ec.europa.eu/articles/6-2
---
