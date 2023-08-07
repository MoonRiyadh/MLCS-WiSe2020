# MLCS-WiSe2020
Universität des Saarlandes - Machine Learning in Cyber Security 2020 - Semester Project

## Team Name: Alpha
Members:
1. H T M A Riyadh(s8htriya@stud.uni-saarland.de)
2. Fahad Hilal (s8fahila@stud.uni-saarland.de)
## My part in this project
It is a two person group project. My part was to develop and implement [1] the program that classifies maleware
from their signatures. I use CNN and image processing technique to achieve our result.  

# Problem Statement
The aim of the project is to perform visualization and classification of malicious
code or programs commonly referred to as malware. The central idea is to
combine deep learning (specifically Convolutional Neural Networks) and image
processing techniques to achieve the objective [1].

# Motivation
In the present age of technology, malware attacks are reported quite frequently.
The main targets of these attacks being both financial institutions and everyday
users. The damage perpetrated by such malware attacks could range from losing
critical or personal data or failure in a nuclear power plant. Thus, our computing
systems need protection from malware attacks round the clock. Automatic
malware identification and detection tools are aimed at addressing this very
problem.

# Proposed Strategy
We leverage the power of CNNs for image classification. We first transform a
malware signature into its binary representation and then convert this binary
into an 8 bit vector followed by transformation to a grayscale image. The final
step is to feed the image into our network for classification.

Reference:
1. _Lakshmanan Nataraj et al. “Malware images: visualization and automatic
classification”. In: Proceedings of the 8th international symposium on visualization for cyber security. 2011, pp. 1–7._
