# NAM 2022 - ML sessions (Wed/Thur)
Convenient static website sharing details on the NAM 2022 ML special sessions

## Wednesday (13 July) 16:30-18:00 (zoom link?)
### [Machine Learning in Modern Astronomy: Learning and Interpreting the Data Driven Universe](https://nam2022.org/science/parallel-sessions/details/2/170)

<table>
  <tr>
    <td> <b>Time</b> </td>
    <td> <b>Speaker</b> </td>
    <td> <b>Talk Title / Abstract </td>
  </tr>
  <tr>
    <td> 16:30-16:35 </td>
    <td> Thomas Killestein </td>
    <td> <b><i> Introduction </i></b> </td>
  </tr>
  <tr>
    <td> 16:35-16:55 </td>
    <td> Emily Hunt </td>
    <td> <b><i> The power (and caveats) of clustering algorithms applied to Gaia data </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> Almost everything in astronomy can be divided into meaningful clusters: clusters of galaxies, star clusters, and even clusters of asteroids. These clusters are hiding in the latest huge astronomical datasets of stars and galaxies, just waiting to be found. And to go about finding them, clustering algorithms – a form of unsupervised machine learning – have seen a surge in popularity for use in exploring and recovering clusters from all kinds of datasets. But with so many different algorithms out there, and so many different datasets each with their own varying challenges, it is hard to choose the right preprocessing steps, algorithm, and postprocessing steps for unsupervised clustering analysis. In the first part of this talk, I will present the results of a comparative study we conducted detecting star clusters in Gaia DR2 with a range of different clustering algorithms [our paper] In this work, we found that: no algorithm was perfect for the task at hand; that choosing the correct parameters for each algorithm is difficult; and that clustering algorithms are easy to misuse, producing completely incorrect results even with off-the-shelf settings that would otherwise appear sensible. Many of these lessons (and the techniques we developed to overcome them) will be relevant to other fields of research. Nevertheless, when applied carefully, clustering algorithms are still an extremely powerful tool for exploratory data analysis in astronomy. In the second part of this talk, I will use our upcoming star cluster catalogue based on a clustering analysis of 729 million stars in Gaia EDR3 with the HDBSCAN algorithm as a case study of the potential of these methods. In particular, I will focus on how I optimised our preprocessing of the data to make such a large dataset even remotely analysable, and how I developed a simple statistical test that quantifies the statistical significance of clusters we detect, allowing us to dramatically reduce the number of false positives in our final catalogue. Finally, I will conclude with some remarks on how some of the remaining flaws with currently available clustering algorithms could be solved – much of which could benefit from collaborations with researchers in computer science fields. Jupyter notebooks & code examples will be provided on GitHub for all of the topics I discuss. </blockquote> </td>
  </tr>
  <tr>
    <td> 16:55-17:10 </td>
    <td> Timothy A Davis </td>
    <td> <b><i> Self-supervised, physics-aware, Bayesian neural networks for modelling <br> galaxy emission-line kinematics </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> In the upcoming decades, large facilities, such as the SKA, will provide resolved observations of the kinematics of millions of galaxies. Kinematic modeling of this data allows us to probe the properties of the stellar, black hole, and dark matter components of galaxies. However, the existing tools to do this are orders of magnitude too slow to cope with the deluge of data expected from the next-generation facilities. I will present details of a new self-supervised, physics-aware, Bayesian neural network architecture which has excellent performance at modeling 2D kinematic moments and extracting physical parameters directly. Models of this type are fully explainable and include uncertainty quantification.  I will showcase their excellent performance by presenting the largest ever study of the Tully-Fisher relation, for ~5000 MaNGA and SAMI galaxies, and discuss further development of this algorithm to full 3D modeling of datacubes. </blockquote> </td>
  </tr>
  <tr>
    <td> 17:10-17:25 </td>
    <td> Matthew Mould </td>
    <td> <b><i> Data-driven inference of gravitational-wave populations with machine <br> learning models </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> The catalog of gravitational-wave events is growing, and so are our hopes of constraining the underlying astrophysics of stellar-mass black-hole mergers by inferring the distributions of, e.g., masses and spins. While conventional analyses parametrize this population with simple phenomenological models, we propose an innovative physics-first approach that compares gravitational-wave data against astrophysical simulations. We combine state-of-the-art techniques from deep learning and hierarchical Bayesian inference with data from the most recent LIGO/Virgo catalog to constrain the repeated black-hole merger scenario, in which first-generation black holes born in stellar collapse may merge repeatedly to form multiple gravitational-wave sources and higher-generation remnants. Deep neural networks allow us to (i) construct a flexible population model that accurately emulates simulations of repeated mergers, (ii) estimate selection effects, and (iii) recover the merger generation branching ratios. Among our results we find that: 40% of first-generation remnants are retained in their host-environments; there is a mass cutoff consistent with current pair-instability supernovae predictions; an extended multimodal spectrum of masses and spins can be accommodated by repeated mergers; in this scenario at least 15% of binaries in the intrinsic population contain a higher-generation black hole. Our machine learning approach to population analysis readily extends to other astrophysical modeling scenarios. </blockquote> </td>
  </tr>
  <tr>
    <td> 17:25-17:40 </td>
    <td> Alessio Spurio Mancini </td>
    <td> <b><i> COSMOPOWER: Deep Learning – accelerated cosmological inference from <br> next-generation surveys </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> Next-generation Large-Scale Structure (LSS) and Cosmic Microwave Background (CMB) surveys will provide us with unprecedented statistical power to assess the nature of the "tension" between LSS and CMB cosmological constraints. However, the computational challenges posed by the unprecedented size of these datasets dangerously hinder the feasibility of their analysis within a rigorous statistical framework for uncertainty propagation, such as the one provided by Bayesian inference. The plethora of contaminants affecting cosmic shear analyses, in particular, urgently calls for the development of sophisticated pipelines that can ensure a level of accuracy in the final cosmological constraints corresponding to the unprecedentedly high precision provided by these future datasets. In my talk I will present COSMOPOWER, an open-source Python framework for Bayesian inference from next-generation CMB and LSS surveys. COSMOPOWER provides orders-of-magnitude acceleration to the inference pipeline by training Deep Learning emulators of matter and CMB power spectra. I will show how these emulators meet the accuracy requirements for application to both currently available cosmological data, such as from the Kilo-Degree Survey (KiDS), as well as to simulated, next-generation data from e.g. a Euclid-like survey. The emulators always recover the fiducial cosmological constraints, while providing a speed-up factor up to Ο(10^4) to the complete inference pipeline. Bayesian parameter contours can thus be recovered in just a few seconds on a common laptop, as opposed to the many hours, days or months of runtime on computer clusters required by standard methods. I will also show an application of COSMOPOWER to the latest cosmic shear data from KiDS to derive constraints on an interacting dark energy model. Throughout the presentation I will present examples from the COSMOPOWER software repository, including Jupyter notebooks presenting examples of training and implementations in real likelihood analyses. I will conclude with an outlook on extensions of COSMOPOWER that are currently being developed to solve long-standing problems in the analysis of current and future cosmological data, such as the effect of the Limber approximation on the computation of LSS power spectra.

 </blockquote> </td>
  </tr>
  <tr>
    <td> 17:40-17:50 </td>
    <td> Joshua William Wilde </td>
    <td> <b><i> Where & Why: Interpreting Convolutional Neural Networks Trained to Identify <br> Strong Gravitational Lenses </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> In the near future Euclid will discover ~10^5 strong gravitational lenses from the ~10^9 objects it will detect during its mission. This will be far too much data for humans to process alone. In recent years machine learning models have been trained to find gravitational lenses (Metcalf et al. 2019). These models have performed well and have detected new gravitational lenses (e.g. Huang et al. 2019). The problem is the question “What is being detected?”. Machine learning approaches such as Convolutional Neural Networks (CNNs) have been described as ‘Black Boxes’. It is not clear what CNNs respond to in the images. We simply do not know if we are detecting the ‘low hanging fruit’ of gravitational lenses. Do these approaches only detected certain types of gravitational lenses such as blue Einstein rings and miss rare lenses such as red Einstein rings? Recently, there has been an attempt to understand how CNNs respond to features in the data, using techniques such as Deep Dream (Mordvintsev et al 2015), Grad-CAM (Selvaraju et al. 2017), and Occlusion maps (Zeiler & Fergus 2014). I have therefore applied these advanced interpretability techniques to a CNN I have created to identify strong gravitational lenses in simulated data, in order to understand the features within the image that the CNN has learnt to associate with strong gravitational lenses. I demonstrated for the first time that such CNNs do not select against compound lenses (i.e. double source plane systems, or Jackpot lenses), obtaining recall scores as high as 76% for compound arcs and 52% for double rings. I verified this performance using Hubble Space Telescope (HST) and Hyper Suprime-Cam (HSC) data of all known compound lens systems. This implies that existing lens finding methodologies should be able to recover compound lensing systems even without further training, albeit not with 100% recall. With the help of the interpretability tools, it is clear that the network is responding to arcs and colour in the case of lensing systems (in agreement with Jacobs et al. 2022) and isolated systems in the case of non-lenses. These interpretability techniques have allowed me to infer positional information about the lens detection in the image. Using post-training interpretability methods can help us understand what the CNN has learnt but cannot allow us to influence what the CNN learns. I have therefore also trained a machine learning model to identify if an image contains a gravitational lens and output the position of the lens within the image. The next step is to build this interpretability directly into our machine learning models, because having a single lens classification value between 0 and 1 will not be enough when applied to future surveys. We need to consider adding a positional output to these models to identify if these models have made a sensible classification or if an unexpected feature in the image has triggered a misclassification. </blockquote> </td>
  </tr>
  <tr>
    <td> 17:50-18:00 </td>
    <td> </td>
    <td> <b><i> Discussion </i></b> </td>
  </tr>
</table>


## Thursday (14 July) 14:30-16:00
### [The Future of Machine Learning in Astronomy](https://nam2022.org/science/parallel-sessions/details/2/171)

<table>
  <tr>
    <td> <b>Time</b> </td>
    <td> <b>Speaker</b> </td>
    <td> <b>Talk Title / Abstract </td>
  </tr>
  <tr>
    <td> 14:30-14:35 </td>
    <td> Michael Walmsley </td>
    <td> <b><i> Introduction </i></b> </td>
  </tr>
  <tr>
    <td> 14:35-14:55 </td>
    <td> Niall Jeffrey </td>
    <td> <b><i> Limits of implicit inference for scientific discovery? </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> Implicit inference methods, including likelihood-free inference and simulation-based inference, that have experienced a huge growth in a very short time. These techniques solve the frequentist or Bayesian inference problem using machine learning approaches (e.g. information extraction and neural density estimation), and have already had significant impact in astronomy. I will discuss how scientific discoveries can be made in this framework despite the complexities and challenges of the forward modelling. I will also consider what happens when we go beyond our “model” – can we hope to discover something new when we have not modelled it a priori? [compare: <a href="https://arxiv.org/abs/2009.08459">ArXiv:2009.08459</a> & <a href="https://arxiv.org/abs/2202.02306">ArXiv:2202.02306</a>] </blockquote> </td>
  </tr>
  <tr>
    <td> 14:55-15:10 </td>
    <td> Prabh Bhambra </td>
    <td> <b><i> Explaining deep learning of galaxy morphology with saliency mapping </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> Physics thrives on model abstraction from complex realities, which black-box deep learning algorithms hinder unless their predictions can be made explainable for future applications. I will present a recently published (Bhambra et al. 2022) demonstration of explainable artificial intelligence (XAI) techniques on Galaxy Zoo morphological classifications of galaxy images. Our XAI approach highlights parts of the images that drive the classification of a certain morphological feature, and I will highlight several cases where the machine learning classification thus becomes more readily explainable than the citizen scientist consensus. I will also show on the example of galactic bar lengths that the XAI outputs can be used to create quantitative predictions of morphological features that are superior to a directly trained machine learning algorithm. </blockquote> </td>
  </tr>
  <tr>
    <td> 15:10-15:25 </td>
    <td> Daniel Muthukrishna </td>
    <td> <b><i> Data-driven Discovery of Supernovae in the New Era of Time-Domain Astronomy </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> Time-domain astronomy has reached an incredible new era where unprecedented amounts of data are becoming available. New large-scale astronomical surveys such as the Legacy Survey of Space and Time (LSST) are going to revolutionise transient astronomy, providing opportunities to discover entirely new classes of transients while also enabling a deeper understanding of known supernovae. LSST is expected to observe over 10 million transient alerts every night, at least two orders of magnitude more than any preceding survey. In this talk, I'll discuss the issue that with such large data volumes, the astronomical community will struggle to identify rare and interesting anomalous transients that have previously been found serendipitously. I'll present two methods of automatically detecting anomalous transient light curves in real-time. The first modelling approach is a probabilistic neural network built using Temporal Convolutional Networks (TCNs) and the second is an interpretable Bayesian parametric model of a transient. We demonstrate our methods' ability to provide anomaly scores as a function of time on light curves from the Zwicky Transient Facility. We show that the flexibility of neural networks, the attribute that makes them such a powerful tool for many regression tasks, is what makes them less suitable for anomaly detection when compared with our parametric model. The parametric model is able to identify anomalies with respect to common supernova classes with low false anomaly rates and high true anomaly rates achieving Area Under the Receiver Operating Characteristic (ROC) Curve (AUC) scores above 0.8 for most rare classes such as kilonovae, tidal disruption events, intermediate luminosity transients, and pair-instability supernovae. Our ability to identify anomalies improves over the lifetime of the light curves. Our framework, used in conjunction with transient classifiers, will enable fast and prioritised follow-up of unusual transients from new large-scale surveys. </blockquote> </td>
  </tr>
  <tr>
    <td> 15:25-15:40 </td>
    <td> Devina Mohan </td>
    <td> <b><i> Uncertainty quantification in deep learning predictions of radio galaxy classification </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> In this talk we show how variational inference can be used to quantify the degree of uncertainty in deep learning predictions of radio galaxy classification. We discuss the model performance and uncertainty calibration for different weight priors and show that a sparse prior produces more well-calibrated uncertainty estimates. We will also discuss how model misspecification and likelihood misclassification affect uncertainty calibration and their effect on the cold posterior effect observed on our work. </blockquote> </td>
  </tr>
  <tr>
    <td> 15:40-15:50 </td>
    <td> Michael James Smith </td>
    <td> <b><i> Realistic galaxy image simulation via score-based generative models </i></b> </td>
  </tr>
  <tr>
    <td colspan="3"> <blockquote><b><i>Abstract:</i></b> We show that a denoising diffusion probabilistic model (DDPM), a class of score-based generative model, can be used to produce realistic mock images that mimic observations of galaxies. Our method is tested with Dark Energy Spectroscopic Instrument (DESI) grz imaging of galaxies from the Photometry and Rotation curve OBservations from Extragalactic Surveys (PROBES) sample and galaxies selected from the Sloan Digital Sky Survey. Subjectively, the generated galaxies are highly realistic when compared with samples from the real data set. We quantify the similarity by borrowing from the deep generative learning literature, using the ‘Fréchet inception distance’ to test for subjective and morphological similarity. We also introduce the ‘synthetic galaxy distance’ metric to compare the emergent physical properties (such as total magnitude, colour, and half-light radius) of a ground truth parent and synthesized child data set. We argue that the DDPM approach produces sharper and more realistic images than other generative methods such as adversarial networks (with the downside of more costly inference), and could be used to produce large samples of synthetic observations tailored to a specific imaging survey. We demonstrate two potential uses of the DDPM: (1) accurate inpainting of occluded data, such as satellite trails, and (2) domain transfer, where new input images can be processed to mimic the properties of the DDPM training set. Here we ‘DESI-fy’ cartoon images as a proof of concept for domain transfer. Finally, we suggest potential applications for score-based approaches that could motivate further research on this topic within the astronomical community. </blockquote> </td>
  </tr>
  <tr>
    <td> 15:50-16:00 </td>
    <td> </td>
    <td> <b><i> Discussion </i></b> </td>
  </tr>
</table>
