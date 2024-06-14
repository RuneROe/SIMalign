# SIMalign




![overview](www/overview.png)

Some text
### [Original paper](https://arxiv.org/abs/2210.01776)

Link to shiny app

<details><summary><b>Citation</b></summary>

If you use this code or the models in your research, please cite the following paper:

```bibtex
    @article{corso2023diffdock,
        title={DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking}, 
        author = {Corso, Gabriele and Stärk, Hannes and Jing, Bowen and Barzilay, Regina and Jaakkola, Tommi},
        booktitle={International Conference on Learning Representations (ICLR)},
        year={2023}
    }
```
</details>

<details open><summary><b>Table of contents</b></summary>

- [Usage](#usage)
  - [Quick Start](#quickstart)
  - [Setup Environment](#environment)
  - [Docking Prediction](#inference)
- [FAQ](#faq)
- [Datasets](#datasets)
- [Replicate results](#replicate)
- [Citations](#citations)
- [License](#license)
- [Acknowledgements](#acknowledgements)
</details>


## Usage  <a name="usage"></a>

### Run online <a name="quickstart"></a>

Link

### Setup Environment  <a name="environment"></a>

We will set up the environment using [Anaconda](https://docs.anaconda.com/anaconda/install/index.html). Clone the
current repo

    git clone https://github.com/gcorso/DiffDock.git

To set up an appropriate environment, navigate to the root of the repository and run the following commands:

    conda create --name SIMalign
    conda activate SIMalign

Download en hel masse

    conda env export > environment.yml

Slet det over her

    conda env create --file environment.yml
    conda activate SIMalign

See [conda documentation](https://conda.io/projects/conda/en/latest/commands/env/create.html) for more information.

