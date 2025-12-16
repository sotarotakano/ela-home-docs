# Welcome to ELA portal page!

<p align="center">
  <img src="images/logo_ELA_latest.png" alt="ELA logo" width="400">
</p>

## Introduction
Energy landscape analysis (ELA) is a systematic method for analyzing an energy landscape represented as a weighted network (Fig. 1).<br>
<br>
![Figure 1: A schematic　of ELA](images/Fig1.png "A schematic illustration of ELA.") 
<div align="center">
    <b>Figure 1. A schematic illustration of ELA.</b> 
</div>

<br>

- In the energy landscape, the nodes of the network represent unique community compositions, and the links represent the transition paths between them.
- The community composition is described as **a binary vector that represents the presence (1) and absence (0) of a species**, and the links connect all nodes that differ only in the presence or absence of one species (Fig. 1B). 
- The nodes are weighted by their energies, and the difference in energy level drives the direction of transitions in community composition (Fig.1D).
- The energy is assigned by **a pairwise maximum entropy model** or its extension with an external force (environmental effect) term (Fig.1C). 

## Platforms
We currently provided several software platforms for running ELA.
<div style="display: flex; justify-content: space-around; text-align: center; gap: 20px;">

  <div>
    <a href="https://github.com/kecosz/rELA" target="_blank">
      <img src="images/R.png" alt="R" width="100">
      <div>rELA</div>
    </a>
  </div>

  <div>
    <a href="https://github.com/sotarotakano/ELApy" target="_blank">
      <img src="images/python.png" alt="Python" width="100">
      <div>ELApy</div>
    </a>
  </div>

  <div>
    <a href="https://github.com/kecosz/ela" target="_blank">
      <img src="images/mathematica.png" alt="Mathematica" width="100">
      <div>ela (Original Mathematica)</div>
    </a>
  </div>

</div>

### R package
R package of ELA is currently available on Windows, Mac(including arm64), and Linux.<br>
<br>
The package is not currently distributed via repositories and can be only installed from 
a local file after the download. <br>

**For details see: <https://github.com/kecosz/rELA>**

### Python package
Python package of ELA is currently available only on Mac(including arm64) or Linux.<br>
<br>
The installation of python package is also not yet supported via online repositories, pip or conda.<br>
The user need to download all the modules from the git repository and need the manual instllation.<br>

**For details see: <https://github.com/sotarotakano/ELApy>**

### Mathematica
Download the package from the github page and run in the Mathematica environment.<br>
**For details see: <https://github.com/kecosz/ela>**


## References and Citations
### Main publication
Suzuki, K., Nakaoka, S., Fukuda, S., & Masuya, H. (2021).
"Energy landscape analysis elucidates the multistability of ecological communities 
across environmental gradients." Ecological Monographs.<br>
<https://esajournals.onlinelibrary.wiley.com/doi/abs/10.1002/ecm.1469>


### ELA in journal articles
Representative articles using ELA packages.

<div style="display: flex; justify-content: space-around; text-align: center; gap: 10px;">

  <div>
    <a href="https://www.pnas.org/doi/10.1073/pnas.2422701122" target="_blank">
      <img src="images/PNAS2025.png" alt="PNAS,2025" width="300">
      <div>PNAS, 2025</div>
    </a>
  </div>

  <div>
    <a href="https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-023-01474-5" target="_blank">
      <img src="images/Microbiome2023.png" alt="Microbiome,2023" width="300">
      <div>Microbiome, 2023</div>
    </a>
  </div>

  <div>
    <a href="https://esajournals.onlinelibrary.wiley.com/doi/10.1002/ecm.1469" target="_blank">
      <img src="images/EcoMono2021.png" alt="EcologicalMonographs,2021" width="300">
      <div>Ecological Monographs, 2021</div>
    </a>
  </div>
</div>


<br>

### Citations
<p align="left">
  <img src="images/totalcitation.png" alt="total citations" width="600">
</p>
[The full article list citing ELA or the related papers.](citations.md)<br>
<br><br>Data collection is conducted using the [SeraAPI](https://serpapi.com/) platform.