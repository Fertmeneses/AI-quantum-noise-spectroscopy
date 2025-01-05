# Deep Learning applied to Spectral Imaging of Magnetic Noise

**[Website in development...]**

As a postdoc in **The City College of New York** (CCNY, USA), I have combined my experimental skills in quantum sensing along with artificial intelligence (AI) techniques. In collaboration with **University College London** (UCL, UK) and **Universidad Nacional de Córdoba** (UNC, Argentina), we published a research article titled **Toward Deep-Learning-Assisted Spectrally Resolved Imaging of Magnetic Noise**, in the journal *Physical Review Applied* in 2022.

[Link to the research article](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.18.024004) 👈🏽.

The full list of authors include:
* Fernando Meneses (CCNY).
* David F. Wise (UCL).
* Daniela Pagliero (CCNY).
* Pablo R. Zangara (UNC).
* Siddharth Dhomkar (UCL).
* Carlos A. Meriles (CCNY).

The main concept of the work was to we probe the response of **quantum defects in diamond** in the presence of a **magnetic environment** and implement a **deep neural network** to extract information about the **noise spectral density**. Our artificial intelligence method was compared to traditional approaches, demonstrating a **better performance and more precise results**.

<center><figure>
  <img src="https://github.com/Fertmeneses/qubit-noise-spectroscopy/blob/main/assets/Image_Concept.jpg?raw=true" alt="Conceptual image"> 
  <figcaption><sup>Conceptual image, AI-generated using the prompt "A small diamond on top of a flat metallic surface with unknown content underneath, with energy waves".</sup></figcaption>
</figure></center>

## Introduction

**Quantum sensing** is a powerful tool where the theory of quantum mechanics can be applied to measure physical properties, for example detecting subtle changes in magnetic fields with great precision. A well-established platform for this technology is the **nitrogen-vacancy (NV) center in diamond**, a specific type of defect within the diamond lattice, in which a nitrogen atom has replaced a carbon atom, next to a spot in which there is a missing carbon atom (vacancy). **This NV defect hosts a quantum system that is extremely sensitive to magnetic fields**, and can be manipulated optically to read out very small variations in the magnetic environment.

**Magnetic signals are usually convoluted with noise originated by random magnetic fluctuations**. This noise, tipycally seen as an obstacle for measurements, can also become a **valuable source of information**, as it may encode critical properties of the local composition and structure of a sample. Consequently, understanding and characterizing the **noise spectral density** is a powerful tool to extract detailed information about a sample's physical properties.

The **problem of decoding magnetic noise** has long been critical for many fields, as it is fundamental for practical applications. **Traditional approaches**, which rely on theoretical models and numerical methods, have made significant progress in the area, but they face **large limitations due to oversimplifications or the extensive experimental data that is required**, which usually compromises the accuracy of the results.

In our research, we address the challenge of **reconstructing the noise spectral density from experimental magnetic measurements**, emphasizing the case of colored noise, where random magnetic fluctuations are mostly distributed within a frequency range. The novelty of our work comes with the application of artificial intelligence tools, showing that **deep learning algorithms can efficiently reconstruct the noise spectral density, employing a minimal experimental dataset**. Our results have benchmarked those of equivalent methodologies using only theoretical and numerical methods, highlighting the **great potential of combining AI-based methods with quantum sensing**.

<center><figure>
  <img src="https://github.com/Fertmeneses/qubit-noise-spectroscopy/blob/main/assets/Noise_PSD_examples.png?raw=true" alt="Signal and Power Spectral Density examples"> 
  <figcaption><sup>(Left) Examples of magnetic signals as a function of time for different colored noises. (Right) Power Spectral Density associated to those signals, with the central (color) frequency indicated by a dashed line, and the half-width bandwidth at half-maximum by a shaded area.</sup></figcaption>
</figure></center>

## Deep Learning algorithm

For the task of determining the Power Spectral Density (PSD) from magnetic signals, we have designed an **AI algorithm** that takes **magnetic timeseries as input data** and **returns the PSD of the underlying magnetic noise** in the frequency space.





Description: auto-encoder.

Some code from Siddharth.

![Autoencoder image](httplink)

## Results

Spectral noise recognition successful. Improved precision compared to numerical methods.

![Noise plots, comparison with numerical methods](httplink)

Possibility to improve with larger experiments, larger training datasets.

## Conclusions

Important milestone in deep learning approaches for magnetic noise spectroscopy. Experimental methods can be combined with theory, simulations and machine learning algorithms, benchmarking results from traditional numerical methods.

![Banner](httplink)

