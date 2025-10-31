---
title: Les signaux
description: Catégories de télémétrie supportées par OpenTelemetry
weight: 11
default_lang_commit: 71833a5f8b84110dadf1e98604b87a900724ac33
drifted_from_default: true
---

L'objectif d'OpenTelemetry est de collecter, traiter et exporter des
**[signaux][signals]**. Les signaux sont des données générées par le système et
décrivant l'activité interne du système d'exploitation et des applications
exécutées sur une plateforme. Un signal peut être quelque chose que vous
souhaitez mesurer à un instant précis, comme par exemple la température ou
l'utilisation mémoire, ou un événement traversant les différents composants de
votre système distribué. Vous avez la possibilité de regrouper plusieurs signaux
ensemble afin d'observer sous différents angles le fonctionnement d'une
technologie.

OpenTelemetry supporte actuellement les:
- [traces](traces)
- [métriques](metrics)
- [logs](logs)
- [bagages](baggage)

Également en cours de développement ou au stade de [propositions]

- Les [évènements], un type spécifique de [logs](logs)
- Les [profils], en cours de développement par le groupe de travail sur le profilage.

[évènements]: /docs/specs/otel/logs/data-model/#events
[Profils]:
  https://github.com/open-telemetry/opentelemetry-specification/blob/main/oteps/profiles/0212-profiling-vision.md
[propositions]:
  https://github.com/open-telemetry/opentelemetry-specification/tree/main/oteps/#readme
[signals]: /docs/specs/otel/glossary/#signals