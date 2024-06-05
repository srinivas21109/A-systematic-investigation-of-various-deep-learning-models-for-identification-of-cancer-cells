# A-systematic-investigation-of-various-deep-learning-models-for-identification-of-cancer-cells


<H2>[Project_report.pdf](https://github.com/user-attachments/files/15580615/Project_report.pdf)</H2>


<H3>Proposed Workflow</H3> 
<BR></BR>
Our proposed workflow includes five main stages: Data Preprocessing, Model Selection and Training, Model Evaluation and Comparison, Model Selection and Fine-Tuning, and Final Evaluation and Results. The diagram below describes the workflow stepwise.

![Picture1](https://github.com/srinivas21109/A-systematic-investigation-of-various-deep-learning-models-for-identification-of-cancer-cells/assets/119849011/270770c6-d2c1-4b76-a82a-f1ce1294e8a7)

<br>
<p align:center>Figure1:The data flow diagram of proposed workflow for pannuke images segmentation.</p>


<H3>Dataset information</H3>
The dataset consists of 481 visual fields, of which 312 are randomly sampled from more than 20K whole slide images at different magnifications, from multiple data sources. In total the dataset contains 205,343 labeled nuclei, each with an instance segmentation mask.

The ground truth annotation samples are shown in the figure below:
![annotations](https://github.com/srinivas21109/A-systematic-investigation-of-various-deep-learning-models-for-identification-of-cancer-cells/assets/119849011/fa713608-3a61-4c63-a6aa-25d659778ea8)

<H3>Data Preprocessing:</H3>

![Picture2](https://github.com/srinivas21109/A-systematic-investigation-of-various-deep-learning-models-for-identification-of-cancer-cells/assets/119849011/68bb2cc3-a6c6-40c7-90ba-a8f46bae070e)

Figure2: Steps involved in data preprocessing.
<br>

<H3>Unet with EfficientnetB7 Encoder</H3>

![Picture3](https://github.com/srinivas21109/A-systematic-investigation-of-various-deep-learning-models-for-identification-of-cancer-cells/assets/119849011/7324544b-c106-42d3-b705-7af7caf440c0)
<p align:center
Figure 3: Architecture of U-net - EfficientNetB7.</p>

<br>

<H3>Detectron2</H3>
![Picture4](https://github.com/srinivas21109/A-systematic-investigation-of-various-deep-learning-models-for-identification-of-cancer-cells/assets/119849011/3594553b-9648-4cf5-8328-2c3488424e9b)
<p align:center
Figure 4: Architecture of Detectron2.</p>


