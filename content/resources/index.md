---
title: Resources
date: 2025-01-01

type: landing

sections:

  # - block: markdown
  #   content:
  #     title: Our Philosophy
  #     text: |
  #       Write whatever you like here.

  #       This is the first editable markdown section.

  #   design:
  #     columns: '1'

  - block: markdown
    content:
      title: Resources for doing science
      text: |
        **Software:**        
        - *Calcium imaging analysis*
          - [Suite2p](https://suite2p.readthedocs.io/en/latest/) - Registration and source extraction.
          - [MLSpike](https://github.com/MLspike/spikes) - Event detection algorithm that works well for extracting climbing fiber events in Purkinje cell dendrites. Used in our [2019](/publication/2019-kostadinov-natureneuro/) and [2025](/publication/2025-kostadinov-biorxiv/) papers.
        - *Electrophysiology analysis*
          - [Kilosort 4](https://kilosort.readthedocs.io/en/latest/) - Semi-automated spike sorter. You can also use this through [SpikeInterface](https://spikeinterface.readthedocs.io/en/stable/).
          - [Phy](https://phy.readthedocs.io/en/latest/) - Our preferred software for manual curation of spike sorted data.
          - [Bombcell](https://github.com/Julie-Fabre/bombcell) - A resource for semi-automated curation of spike-sorted data. Used to get clean ground-truth units in [Beau et al., 2025](/publication/2025-beau-cell/).
          - [Awesome Neuropixels](https://github.com/Julie-Fabre/awesome_neuropixels) - a compiled set of resources for state-of-the-art use of Neuropixels probes.
          - [NeuroPyxels](https://github.com/m-beau/NeuroPyxels) - Friend of the lab [Maxime Beau](/author/maxime-beau)'s analysis package that has lots of helpful functions for analyzing and plotting data in Python. Designed for Neuropixels electrophysiology data but useful for all kinds of analysis.
        - *General data analysis*
          - [dkNeuroLab Github page](https://github.com/dkneurolab) - where you can find code associated with our papers.
          - [GLMnet](https://glmnet.stanford.edu/index.html) - Generalized Linear Model fitting software, See Jonathan Pillow’s [tutorial](https://www.youtube.com/watch?v=NFeGW5ljUoI&t=2642s) at the 2018 Cosyne meeting for a very useful primer.

        **Hardware:**
        - Microscopes - We have worked extensively with Dale Elgar at [Cosys](https://www.cosys.org.uk/).
        - We try to build as much of our equipment as possible in-house. Stay tuned for an detailed description of our behavioural setups.

        **Textbooks:**
        - [Spikes](https://mitpress.mit.edu/books/spikes) - a surprisingly accessible computational neuroscience textbook.
        - [Foundations of Cellular Neurophysiology](https://mitpress.mit.edu/books/foundations-cellular-neurophysiology) - the best cellular neurophysiology book. Very useful for grounding your systems neuroscience understanding in biophysics.
        - [The Cerebellum as a Neuronal Machine](https://link.springer.com/book/10.1007/978-3-662-13147-3) - a classic piece of text.
        
    design:
      css_class: resources-section
      columns: '1'

  - block: markdown
    content:
      title: Building a better scientific community
      text: |
        **Primary literature, essays, and reviews that quantify inequality:**
        - [Indira Raman: Power analysis](https://elifesciences.org/articles/52232)
        - [Dworkin et al., 2020, The extent and drivers of gender imbalance in neuroscience reference lists](https://www.nature.com/articles/s41593-020-0658-y) - It's probably worse than you think.
        - Racial disparities in funding rates in the US at the [NIH](https://elifesciences.org/articles/65697) and [NSF](https://elifesciences.org/articles/83071). Data from 2021-22.
        - [The UK's demographics stats for academia 2024/25](https://www.hesa.ac.uk/data-and-analysis/sb274/figure-5) - yikes.
        
        **Links and resources:**
        - [BiasWatchNeuro's lists of diverse speakers]()
        - [The SAFE Handbook](https://elifesciences.org/articles/108853) - a tool for improving lab culture
        
    design:
      css_class: resources-section
      columns: '1'

---