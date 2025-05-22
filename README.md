# IMAGE-BASED-TIME-CLASSIFICATION
With the rapid advancement of computer vision and image analysis technologies, extracting 
contextual information from visual data has become a vital area of research. One particularly valuable 
contextual cue is the time of day at which an image was captured. Temporal classification of images—
 distinguishing between categories such as morning, noon, afternoon, evening, and night—can 
significantly benefit a variety of applications, including smart surveillance, autonomous driving, 
environmental monitoring, and content-based image retrieval. 
In this project, we propose a lightweight yet effective rule-based framework for classifying the time of 
day in natural scene images. Unlike conventional approaches that depend on deep learning models 
and extensive annotated datasets, our method focuses on handcrafted visual features, including 
brightness, sky brightness, contrast, color warmth, and blue ratio. These features are extracted through 
classical image processing techniques and used to infer both the general period (day or night) and the 
specific time block. 
To enable supervised evaluation without the overhead of manual labeling, ground truth labels were 
automatically derived from timestamp information embedded in image filenames. A custom rule
based prediction function was then developed to classify each image accordingly. 
This study aims to evaluate the effectiveness and interpretability of simple, handcrafted visual cues in 
the task of temporal image classification. Furthermore, we analyze inconsistencies and edge cases 
within the dataset that may affect prediction performance, establishing a solid foundation for future 
integration with data-driven machine learning models. 
