![banner](banner.gif)

<p align="center">
	<code> [ Have a look at the presentation slides: <a href="slides-OFFZONE.pdf"><code>slides-OFFZONE.pdf</code></a> / <a href="slides-ODS.pdf"><code>slides-ODS.pdf</code></a> ] </code><br>
  	<code> [ Related demonstration (<a href="https://github.com/jupyter/notebook">Jupyter</a> notebook): <a href="demo.ipynb"><code>demo.ipynb</code></a> ] </code><br><br>
  	<b>
		<a href="#-overview">Overview</a> | 
		<a href="#%EF%B8%8F-attacks">Attacks</a> | 
		<a href="#-tools">Tools</a> | 
		<a href="#-more-on-the-topic">More on the topic</a>
	</b>
</p><br>

> An overview of black-box [attacks](#%EF%B8%8F-attacks) on AI and [tools](#-tools) that might be useful during security testing of machine learning models.



# 📦 Overview

[`demo.ipynb`](demo.ipynb):<br>
A demonstration of use of multifunctional [tools](#-tools) during security testing of machine learning models [`digits_blackbox`](https://github.com/Azure/counterfit/tree/main/counterfit/targets/digits_blackbox) & [`digits_keras`](https://github.com/Azure/counterfit/tree/main/counterfit/targets/digits_keras) trained on the MNIST dataset and provided in [Counterfit](https://github.com/Azure/counterfit/tree/main/counterfit/targets) as example targets.<br><br>

Slides:
<br>&emsp;–&emsp;Machine Learning in products
<br>&emsp;–&emsp;Threats to Machine Learning models
<br>&emsp;–&emsp;Example model overview
<br>&emsp;–&emsp;Evasion attacks
<br>&emsp;–&emsp;Model inversion attacks
<br>&emsp;–&emsp;Model extraction attacks
<br>&emsp;–&emsp;Defences
<br>&emsp;–&emsp;Adversarial Robustness Toolbox
<br>&emsp;–&emsp;Counterfit<br>


# ⚔️ Attacks
- **Model inversion attack**: `MIFace` — [code](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/attacks/inference/model_inversion/mi_face.py) / [docs](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/attacks/inference/model_inversion.html#model-inversion-miface) / 🔗[DOI:10.1145/2810103.2813677](https://dl.acm.org/doi/10.1145/2810103.2813677)
- **Model extraction attack**: `Copycat CNN` — [code](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/attacks/extraction/copycat_cnn.py) / [docs](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/attacks/extraction.html#copycat-cnn) / 🔗[arXiv:1806.05476](https://arxiv.org/abs/1806.05476)
- **Evasion attack**: `Fast Gradient Method (FGM)` — [code](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/attacks/evasion/fast_gradient.py) / [docs](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/attacks/evasion.html#fast-gradient-method-fgm) / 🔗[arXiv:1412.6572](https://arxiv.org/abs/1412.6572)
- \+ Evasion attack: `HopSkipJump` — [code](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/attacks/evasion/hop_skip_jump.py) / [docs](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/attacks/evasion.html#hopskipjump-attack) / 🔗[arXiv:1904.02144](https://arxiv.org/abs/1904.02144)<br>


# 🔧 Tools
&emsp;–&emsp;\[ Trusted AI, IBM ] Adversarial Robustness Toolbox (ART): [:octocat: Trusted-AI/adversarial-robustness-toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox)
<br>&emsp;–&emsp;\[ Microsoft Azure ] Counterfit: [:octocat: Azure/counterfit](https://github.com/Azure/counterfit)<br>


# 📑 More on the topic

- `adversarial examples` `evasion attacks`<br>
How MIT researchers made Google's AI think tabby cat is guacamole:&ensp;[overview](https://www.labsix.org/physical-objects-that-fool-neural-nets/) / 🔗[arXiv:1707.07397](https://arxiv.org/abs/1707.07397) + [arXiv:1804.08598](https://arxiv.org/abs/1804.08598)

- `model inversion attacks`<br>
Apple's take on model inversion:&ensp;[overview](https://machinelearning.apple.com/research/reconstructing-training-data) / 🔗[arXiv:2111.03702](https://arxiv.org/abs/2111.03702)

- `model inversion attacks`<br>
Google's demonstration of extraction of training data that the GPT-2 model has memorized:&ensp;[overview](https://ai.googleblog.com/2020/12/privacy-considerations-in-large.html) / 🔗[arXiv:2012.07805](https://arxiv.org/abs/2012.07805)

- [`attacks on AI`](https://portswigger.net/daily-swig/take-threats-against-machine-learning-systems-seriously-security-firm-warns)
[`adversarial attacks`](https://portswigger.net/daily-swig/adversarial-attacks-against-machine-learning-systems-everything-you-need-to-know)
[`poisoning attacks`](https://portswigger.net/daily-swig/triggerless-backdoors-can-infect-machine-learning-models-without-leaving-a-trace-research)
[`model inference attacks`](https://portswigger.net/daily-swig/inference-attacks-how-much-information-can-machine-learning-models-leak)<br>
→ Posts on PortSwigger's "The Daily Swig" by [Ben Dickson](https://twitter.com/bendee983)
