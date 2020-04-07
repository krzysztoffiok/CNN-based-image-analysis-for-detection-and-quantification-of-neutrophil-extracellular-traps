# Convolutional-neural-networks-based-image-analysis-for-detection-and-quantification-of-neutrophil-ex
Repository containing dataset of images used in:
Manda-Handzlik, A., Fiok, K., Cieloch, A., Heropolitanska-Pliszka, E., & Demkow, U. (2020). Convolutional Neural Networks–Based Image Analysis for the Detection and Quantification of Neutrophil Extracellular Traps. Cells, 9(2), 508.</br>

Authors:
Aneta Manda-Handzlik1,2, Krzysztof Fiok3, Adrianna Cieloch1, Edyta Heropolitańska-Pliszka4 and Urszula Demkow1 </br>
1: Department of Laboratory Medicine and Clinical Immunology of Developmental Age, Medical University of Warsaw, Zwirki i Wigury 63a Street, 02-091, Warsaw, Poland,</br>
2: Postgraduate School of Molecular Medicine, Medical University of Warsaw, Zwirki i Wigury 61 Street, 02-091, Warsaw, Poland,</br>
3: Department of Industrial Engineering & Management Systems, University of Central Florida, 4000 Central Florida Blvd., P.O. BOX 162993, Orlando, FL 32816-2993, USA,</br>
4: Department of Immunology, The Children's Memorial Health Institute, Aleja Dzieci Polskich 20, 04-730, Warsaw, Poland </br>

The dataset is divided into 4 .zip files containing:
- train_val_split_used_for_training.zip - images and annotations (in mscoco json format) used during training of the model described in paper;
- large_validation_set.zip - images and annotations (in pascalvoc xml format and mscoco json format) used for validation of the model after training procedure was completed;
- for_coco_evaluation.zip - small set of images for evaluation; and
- in the "release" section "original_uncompressed_images_with_pascalvoc_annotations.zip" containing uncompressed images used for training of the model can be found.

Example detections carried out by the model described in paper:

<img src="https://github.com/krzysztoffiok/CNN-based-image-analysis-for-detection-and-quantification-of-neutrophil-extracellular-traps/blob/master/images/4_2%20Per%202h%20006_scale.jpg" width=640 height=512>

<img src="https://github.com/krzysztoffiok/CNN-based-image-analysis-for-detection-and-quantification-of-neutrophil-extracellular-traps/blob/master/images/4_4%20Per%202h%20002_scale.jpg" width=640 height=512>
