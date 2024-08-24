# Korean-Beef-Grading

Pre-trained for recognizing subtle color difference
with SimCLR & NT-Xent Loss (unsupervised learning)

Fine-tuned with ResNet50 with Labeled Training set

Data Source from 한국축산데이터
(1080*1920 pixel, color-depth = 24bit)

Used Augmentation by Random Apply Color Jitter in Pre-training
(brightness =0.5, contrast =0.5, saturation=0.5, hue=0.2), p=0.8 </br>
ResNet50 (used normalize RGB mean & std calculated from our training set)

Reference from</br>
"A Simple Framework for Contrastive Learning of Visual Representations" by Chen et al.(2020)</br>
한국축산 데이터 used 3,000 imaged for each grade(3, 2, 1, 1+, 1++)
