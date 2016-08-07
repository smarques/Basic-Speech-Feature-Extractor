—Basic Speech Feature Extracor-
https://github.com/composingcap/Basic-Speech-Feature-Extractor

This is a Max/MSP implementation of basic vowel and concinant reconition using the zsa descriptors written by Mikhail Malt (Ircam) & Emmanuel Jourdan (e--j dev).

To run open the maxproject file in Max MSP.

---Implementation---
All externals are includes in the project, so just open the project in Max and connect it to wekinator.  This feature extractor uses a measure of symetry accross frequency bins (symetrical distributions in indicate noise or concinants), a standard deviation of spectrum bands (a larger stard dev will indicate noise as well) and 24 mel coeficents which do the majoraty of the identification.

The max patch includes a simple noise gate to help reduce unwanted training data when a user is training the model.

The patch outputs 26 features by default

Pre-recorded examples are in the wekitester folder in the form of a wekinator project. There is also a testing patch in the project. 
