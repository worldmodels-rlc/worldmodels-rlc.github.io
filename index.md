---
title: Home
---

# Model-Based Reinforcement Learning in the Era of Generative World Models

**MBRL-GWM Workshop @ [RLC 2026](https://rl-conference.cc/) — August 15, 2026**

Model-based reinforcement learning (MBRL) offers a principled framework for data-efficient policy learning and planning. However, the practical success of MBRL has been historically bottlenecked by the difficulty of learning scalable, accurate dynamics models. Traditional models struggle with high-dimensional, noisy state spaces and suffer from compounding transition errors, leading to poor policy optimization.

This workshop focuses on the next frontier of MBRL: learning robust policies from highly capable, large-scale learned simulators. By utilizing recent advances in **generative world models**---large-scale neural models trained to synthesize plausible future observations---as a mechanism for high-fidelity experience generation, we unlock new paradigms for robust dynamics modeling, zero-shot planning, and offline policy optimization within MBRL. We also explore complex, noisy domains like embodied AI as practical testbeds for these algorithmic advancements.

The workshop will gather experts to discuss how to solve compounding errors in transition dynamics, leverage synthetic experience for RL pre-training, and reliably extract robust policies from learned models.

## Core Topics

- **Scalable Dynamics for MBRL:** Adapting high-capacity generative architectures (sequence or video models) to serve as rigorous transition dynamics models, grounded and free of compounding errors during long-horizon planning.
- **Policy Extraction and Planning:** Designing RL algorithms to exploit infinite synthetic experience — effective paradigms for control-relevant abstractions, exploration, and zero-shot planning within learned simulators.
- **Evaluating MBRL in Complex Domains:** Achieving zero-shot generalization in new, noisy environments and successfully crossing the sim-to-real gap for robust embodied AI deployment.

## Key Dates

| Event | Date |
|---|---|
| Submission Deadline | May 15, 2026 (AOE) |
| Author Notification | May 29, 2026 (AOE) |
| Workshop | August 15, 2026 |

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

> Workshop on Model-Based Reinforcement Learning and Generative World Models, co-located with RLC 2026.
>
> <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year }} — [source code]({{ site.repo }}).
