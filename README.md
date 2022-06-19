![banner](banner.gif)
<p align="center">
	<a href="demo.ipynb"><code> [ demo.ipynb ] </code></a><br>
</p><br>

> A demonstration of use of multifunctional [tools](#-tools) during security testing of the machine learning model [`digits_blackbox`](https://github.com/Azure/counterfit/tree/main/counterfit/targets/digits_blackbox) that is provided in [Counterfit](https://github.com/Azure/counterfit/tree/main/counterfit/targets) as an example target.<br>
> 
> // Made as a part of my Call For Papers application<br>


## ⚔️ Attacks
- Model inversion attack: `MIFace` — [code](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/attacks/inference/model_inversion/mi_face.py) / [docs](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/attacks/inference/model_inversion.html#model-inversion-miface) / 🔗[DOI:10.1145/2810103.2813677](https://dl.acm.org/doi/10.1145/2810103.2813677)
- Model extraction attack: `Copycat CNN` — [code](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/attacks/extraction/copycat_cnn.py) / [docs](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/attacks/extraction.html#copycat-cnn) / 🔗[arXiv:1806.05476](https://arxiv.org/abs/1806.05476)
- Evasion attack: `Fast Gradient Method (FGM)` — [code](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/attacks/evasion/fast_gradient.py) / [docs](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/attacks/evasion.html#fast-gradient-method-fgm) / 🔗[arXiv:1412.6572](https://arxiv.org/abs/1412.6572)
- \+ Evasion attack: `HopSkipJump` — [code](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/art/attacks/evasion/hop_skip_jump.py) / [docs](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/modules/attacks/evasion.html#hopskipjump-attack) / 🔗[arXiv:1904.02144](https://arxiv.org/abs/1904.02144)

## 🔧 Tools
- Adversarial Robustness Toolbox (ART): [:octocat: Trusted-AI/adversarial-robustness-toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox)
- Microsoft Azure Counterfit: [:octocat: Azure/counterfit](https://github.com/Azure/counterfit)
