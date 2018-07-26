# About BreastScreening Project

<a href="https://github.com/MIMBCD-UI/" title="Meta" target="_blank">
  <img src="https://github.com/MIMBCD-UI/meta/blob/master/headers/breast_cancer_women.png" alt="header" />
</a>

## Introduction

More Specifically, this project deals with the use of a recently proposed technique in literature: [Deep Convolutional Neural Networks (CNNs)](https://en.wikipedia.org/wiki/Convolutional_neural_network). These deep networks will incorporate information from several different modes: magnetic resonance imaging volumes (MRI), ultrasound images, mammographic images (both views [CC](http://radiopaedia.org/articles/craniocaudal-view) and [MLO](http://radiopaedia.org/articles/mediolateral-oblique-view)) and text. The proposed algorithm, called for multimodality CNNs (MMCNNs) will have the ability to process multimodal information at an unified and sustained manner. This methodology needs to "learn" what are the masses and calcifications.

So that is necessary to collect the [ground truth](https://en.wikipedia.org/wiki/Ground_truth), or notes of the masses and calcifications provided by medical experts. For the collection of these notes, the design and development of an interface is necessary allows the user (in this case, the medical specialist) to display various types of image (i.e., ultrasound, MRI and mammography), and that also allows for user interaction, particularly in providing the notes of the masses and calcifications. For these reasons, it is crucial for the development of this project, cooperation with experts providing the above notes.

## Goals

Development of an Assistant for Diagnosis of Breast Cancer in Medical Imaging.

It is intended to develop an Assitant for monitoring and diagnosis of breast lesions in various medical imaging modalities. Imaging modalities to include in the work are:

* [Mammography](https://en.wikipedia.org/wiki/Mammography) (including the views caudal-skull and oblique);
* [Ultrasound](https://en.wikipedia.org/wiki/Ultrasound);
* [MRI](https://en.wikipedia.org/wiki/Magnetic_resonance_imaging) volumes;

With protocol already signed with the [Hospital Fernando Fonseca](http://www.hff.min-saude.pt/), it is intended that this interface has two features:

**(i)** - Build a database with annotations in multimodality mammography image.

Provide the user (doctor) facility to draw / write down masses and calcifications, as well as the corresponding [BI-RADS](https://en.wikipedia.org/wiki/BI-RADS) for each imaging modality. This annotation process can be built during the examination, and thus it is possible to build a database of medical notes.

**(ii)** - Follow-up of the patient. With this feature is to allow the doctor automate a multimodality inspection for the patient.

Based on the patient's identification (eg, via a query on the ID), and for a given type of mammography imaging, the system must return all images of this patient over a period of time (eg. Two or more years) entered by the doctor, and show these images (pre-recorded). This feature is critical for diagnosis because it allows, through information visualization, observing not only the calcifications density and the morphological evolution of the masses in that time period.
