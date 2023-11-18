**ABSTRACT:**
Now a day’s human behavior and activity pattern researches are more important in surveillance. Detection and tracking the object of behavior is important factor in video surveillance system. If any problem is happening in crowded area based on behaviors of persons then it depends on two types spatial and temporal. Over a last decade it has been seen the rapid growth and an extraordinary improvement in real-time video analysis. Main goal of video analytics is to identify the potential threaten events with less or no human intervention. Video surveillance is a prominent area of research which includes recognition of human activities and categorization of them into usual (normal), unusual (abnormal) or suspicious activities. Main task is to locating unusual events in videos by using some surveillance system which can be manual, semi-automatic or fully automatic. Manual surveillance system is fully dependent on human. It required manual labor to analyze behavior or to make difference between abnormal and normal behavior. Semiautomatic system required less human intervention while fully automatic are intelligent and smart video surveillance system which doesn’t required human intervention to make decision. The other method of intrusion detection is face recognition. The dataset of criminals is created and stored in system, when criminal face is recognized by camera it will create alert message to system and notify about it. Face recognition is done by OpenCV library in python. Internally image processing and deep learning is done in this process of recognition. Because of such advance technique system become more accurate.
**INTRODUCTION:**
Simple activities can be modeled accurately as Markov Chains. However, complex or unfamiliar activities are often difficult to understand and model. For example, a researcher studying activities of daily living for a person with dementia will have a difficult time fitting a model unless she is an expert in dementia and understands its related behavioral science.

**OBJECTIVE:** 
  The goal of activity recognition is to recognize common human activities in real life settings.
  Accurate activity recognition is challenging because human activity is complex and highly diverse.
  Several probability-based algorithms have been used to build activity models.

**EXISTING SYSTEM:**
  Numerous attempts have been made in this field to automatize video surveillance but      each and every approach has its own pros and cons.
  On the basis of prior knowledge and human involvement in the learning process, the research in human activity recognition can be categorized as supervised, unsupervised and semi supervised.
  
**PROPOSED SYSTEM:**
  Unusual activity recognition systems are developed to make surveillance system smarter and more intelligent. 
  Main aim is to detect suspicious or abnormal activities in videos to avoid future happening or to give alert whenever any type of mishappening occur. 
  These anomalous activity recognition systems classify normal and abnormal activities of objects. Most of previous research in anomalous or suspicious activity recognition has focused on behavior understanding by training the system manually. 
  Some of work shows unsupervised learning methodologies for activity detection.

**VIDEO STREAMING:**
       In this process we are capturing video from video devices and that video stream we are      uploading into a Resnet model. Then the processing was started as detecting the activity.
       
**IMPORT MODEL:**
       ResNet, short for Residual Networks is a classic neural network used as a backbone for many computer visions tasks. he fundamental breakthrough with ResNet was it allowed us to train extremely deep neural networks with 150+layers successfully.

**NORMALIZATION:**
      Image Normalization is a process in which we change the range of pixel intensity values to make the image more familiar or normal to the senses, hence the term normalization. Often image normalization is used to increase contrast which aids in improved feature extraction or image segmentation.

**ACTIVITY DETECTION:**
      Then finally using Resnet detecting the activity of the person which passing on the video. Here based on the human behavior system detecting the activities of that person.
      
**ALGORITHM:**
  ResNet
    When ResNet was first introduced, it was revolutionary for proving a new solution to a huge problem for deep neural networks at the time: the vanishing gradient problem. Although neural networks are universal function approximators, at a certain threshold adding more layers makes training become slower and makes the accuracy saturate. For instance, ResNet on the paper is mainly explained for ImageNet dataset.
    So, let’s explain this repeating name, block. Every layer of a ResNet is composed of several blocks. This is because when ResNets go deeper, they normally do it by increasing the number of operations within a block, but the number of total layers remains the same. An operation here refers to a convolution a batch normalization and a ReLU activation to an input, except the last operation of a block, that does not have the ReLU.
