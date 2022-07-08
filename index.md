## NAM 2022 - ML sessions
### Session Location: [Social Sciences](http://campus-cms.warwick.ac.uk/share/872acbbad9752bf58e4a5e3be2dd82ad) --- [Room S0.11](https://theta360.com/s/cCEqLppMmQ9eEYx8xXQbHndlQ) (Ground Floor; [annoated campus map](https://drive.google.com/file/d/1VKFuRkjLWJAlNgjQUU6VqrXfbyIzsuFk/view))

We are jointly organising two Parallel Sessions to discuss how machine learning supports our science and how we might overcome the challenges it now faces. The [timetable](#timetable) is available below.

- Machine Learning in Modern Astronomy (Techniques2)
- The Future of Machine Learning in Astronomy (Techniques3)

Techniques2 focuses on recent innovative and successful applications of ML in astronomy [(full proposal here)](https://nam2022.org/science/parallel-sessions/details/2/170). This session will showcase the crucial role machine learning plays in enabling science.

Techniques3 focuses on the challenges such methods face and their speculative solutions [(full proposal here)](https://nam2022.org/science/parallel-sessions/details/2/171). This session will consider how we can shape the future of machine learning to create the tools we need. 

## Abstract Submission

Abstract submission is now **closed**. We recieved 44 abstracts across both sessions (2x 1.5 hours). We look forward to seeing your work at NAM 2022!

Given the sessions' popularity, we will only be considering late abstracts in exceptional circumstances (e.g. personal emergency). Please write to the organisers (see [Contact](#contact)) with a brief explanation if you would like to submit a late abstract. Do NOT include the abstract itself.

For reference, you can review the original abstract submission instructions [here](abstract_submission_reference.md).

## Timetable

The draft NAM 2022 schedule suggests the following session times:

- Techniques2 on [Wednesday](https://github.com/mwalmsley/nam-ml/edit/gh-pages/index.md#wednesday-13-july-1630-1800) at 16:30-18:00
- Techniques3 on [Thursday](https://github.com/mwalmsley/nam-ml/edit/gh-pages/index.md#thursday-14-july-1430-1600) at 14:30-16:00

### Wednesday (13 July) 16:30-18:00
#### Technique2: Machine Learning in Modern Astronomy: Learning and Interpreting the Data Driven Universe

- 16:30-16:35 \-\- Thomas Killestein \-\- **Introduction**
- 16:35-16:55 \-\- Emily Hunt \-\- 

  **The power (and caveats) of clustering algorithms applied to Gaia data**
  > *The speaker will present the results of a comparative study they conducted detecting star clusters in Gaia DR2 using a range of different clustering algorithms. In this talk, they will (1) discuss the challenges in applying clustering algorithms, (2) provide a star cluster catalogue based on a clustering analysis of 729 million stars in Gaia EDR3 using the HDBSCAN algorithm, and (3) comment on how to (possibly) reslove some remaining issues in clusteing algorithms. Jupyter notebooks and codes will be available on GitHub.*

- 16:55-17:10 \-\- Timothy A Davis \-\- 

  **Self-supervised, physics-aware, Bayesian neural networks for modelling galaxy emission-line kinematics**
  > *The speaker will present a new self-supervised, physics-aware, Bayesian neural network architecture, which has excellent performance at modeling 2D kinematic moments and extracting physical parameters directly. Models of this type are fully explainable and include uncertainty quantification. They will showcase their excellent performance by presenting the largest ever study of the Tully-Fisher relation, for ~5000 MaNGA and SAMI galaxies, and discuss further development of this algorithm to full 3D modeling of datacubes.*

- 17:10-17:25 \-\- Matthew Mould \-\- 

  **Data-driven inference of gravitational-wave populations with machine learning models**
  > *The speaker will present deep learning models with hierarchical Bayesian inference that uses data from the most recent LIGO/Virgo catalog to constrain the repeated black-hole merger scenario. Among their results, they found that: 40% of first-generation remnants are retained in their host-environments; there is a mass cutoff consistent with current pair-instability supernovae predictions; an extended multimodal spectrum of masses and spins can be accommodated by repeated mergers; in this scenario at least 15% of binaries in the intrinsic population contain a higher-generation black hole.*

- 17:25-17:40 \-\- Alessio Spurio Mancini \-\- 

  **COSMOPOWER: Deep Learning – accelerated cosmological inference from next-generation surveys**
  > *The speaker will present COSMOPOWER, an open-source Python framework for Bayesian inference from next-generation CMB and LSS surveys. COSMOPOWER provides orders-of-magnitude acceleration to the inference pipeline by training Deep Learning emulators of matter and CMB power spectra. They will show how these emulators meet the accuracy requirements for application to both currently available cosmological data, such as from the Kilo-Degree Survey (KiDS), as well as to simulated, next-generation data from e.g. a Euclid-like survey. Furthermore, they will present an application of COSMOPOWER to the latest cosmic shear data from KiDS to derive constraints on an interacting dark energy model.*

- 17:40-17:50 \-\- Joshua William Wilde \-\- 

  **Where & Why: Interpreting Convolutional Neural Networks Trained to Identify Strong Gravitational Lenses**
  > *The speaker will present the use of interpretability techniques such as Deep Dream (Mordvintsev 2015), Grad-CAM (Selvaraju 2017), and Occlusion maps (Zeiler & Fergus 2014) to help them understand the features associated with strong gravitational lenses in images when using a CNN. They demonstrated that CNNs do not select against compound lenses and obtained recall scores: 76% for compound arcs and 52% for double rings. With the interpretability tools, it shows that the network is responding to arcs and colour when identifying lensing systems (in agreement with Jacobs 2022) and isolated systems when identifying non-lenses.*

- 17:50-18:00 \-\- **Discussion**

### Thursday (14 July) 14:30-16:00
#### Technique3: The Future of Machine Learning in Astronomy

- 14:30-14:35 \-\- Michael Walmsley \-\- **Introduction**
- 14:35-14:55 \-\- Niall Jeffrey \-\- 

  **Limits of implicit inference for scientific discovery?**
  > *The speaker will present the implicit inference methods including likelihood-free inference and simulation-based inference. These techniques solve the frequentist or Bayesian inference problem using machine learning approaches (e.g. information extraction and neural density estimation), and have already had significant impact in astronomy. They will further discuss (1) how scientific discoveries can be made in this framework despite the complexities and challenges of the forward modelling and (2) what happens when we go beyond our “model” – can we hope to discover something new when we have not modelled it a priori? \[compare: [ArXiv:2009.08459](https://arxiv.org/abs/2009.08459) & [ArXiv:2202.02306](https://arxiv.org/abs/2202.02306)\]*

- 14:55-15:10 \-\- Prabh Bhambra \-\- 

  **Explaining deep learning of galaxy morphology with saliency mapping**
  > *The speaker will present a recently published (Bhambra 2022) demonstration of explainable artificial intelligence (XAI) techniques on Galaxy Zoo morphological classifications of galaxy images. The XAI approach highlights parts of the images that drive the classification of a certain morphological feature. They will demostrate several cases where the machine learning classification becomes more readily explainable than the citizen scientist consensus, and examples of galactic bar lengths that the XAI outputs can be used to create quantitative predictions of morphological features that are superior to a directly trained machine learning algorithm.*

- 15:10-15:25 \-\- Daniel Muthukrishna \-\- 

  **Data-driven Discovery of Supernovae in the New Era of Time-Domain Astronomy**
  > *The speaker will present two methods of automatically detecting anomalous transient light curves in real-time. The first modelling approach is a probabilistic neural network built using Temporal Convolutional Networks (TCNs) and the second is an interpretable Bayesian parametric model of a transient. They demonstrate their methods' ability to provide anomaly scores as a function of time on light curves from the Zwicky Transient Facility. They show that the flexibility of neural networks, the attribute that makes them such a powerful tool for many regression tasks, is what makes them less suitable for anomaly detection when compared with the parametric model. The parametric model is able to identify anomalies with respect to common supernova classes with low false anomaly rates and high true anomaly rates achieving Area Under the Receiver Operating Characteristic (ROC) Curve (AUC) scores above 0.8 for most rare classes such as kilonovae, tidal disruption events, intermediate luminosity transients, and pair-instability supernovae.*

- 15:25-15:40 \-\- Devina Mohan \-\- 

  **Uncertainty quantification in deep learning predictions of radio galaxy classification**
  > *The speaker will present how variational inference can be used to quantify the degree of uncertainty in deep learning predictions of radio galaxy classification. They discuss the model performance and uncertainty calibration for different weight priors and show that a sparse prior produces more well-calibrated uncertainty estimates. They also discuss how model misspecification and likelihood misclassification affect uncertainty calibration and the  effect on the cold posterior effect observed on their work.*

- 15:40-15:50 \-\- Michael James Smith \-\- 

  **Realistic galaxy image simulation via score-based generative models**
  > *The speaker will present that a denoising diffusion probabilistic model (DDPM), a class of score-based generative model, can be used to produce realistic mock images that mimic observations of galaxies. The method is tested with Dark Energy Spectroscopic Instrument (DESI) grz imaging of galaxies from the Photometry and Rotation curve OBservations from Extragalactic Surveys (PROBES) sample and galaxies selected from the Sloan Digital Sky Survey. They will demonstrate two potential uses of the DDPM: (1) accurate inpainting of occluded data, such as satellite trails, and (2) domain transfer, where new input images can be processed to mimic the properties of the DDPM training set.*

- 15:50-16:00 \-\- **Discussion**


## Contact

Please reach out to the proposers if you have any questions, ideas, or feedback.

Techniques2 is proposed by Thomas Killestein ([email](mailto:t.killestein@warwick.ac.uk), [website](https://warwick.ac.uk/fac/sci/physics/research/astro/people/thomaskillestein)). The organising committee is David Armstrong, Eliot Ayache, Joe Lyman, and Azib Norazman.

Techniques3 is proposed by Mike Walmsley ([email](mailto:michael.walmsley@manchester.ac.uk), [website](https://walmsley.dev/)). The organising committee is Ashley Spindler, Anna Scaife, Chris Lintott, and Ting-Yun Cheng.

