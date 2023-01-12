## Detection of Typhoon Damaged Regions on UAV Captured Rice Field Images Using an Ensemble of CNN and Artificial Neural Network

### Abstract

Typhoons can cause extreme damages to rice fields causing revenue loss for farmers especially if not addressed early. However, timely damage assessment is difficult due to the scale of rice fields. In this study, we utilized images captured by a commercially available unmanned aerial vehicle (UAV) to create a model that can identify rice plant damage, specifically lodging, caused by typhoons. Local officials helped gather and establish ground truth data captured in a period of seven to ten days after a typhoon. The images were divided into uniform-sized tiles and served as the dataset for the baseline CNN model which yielded 87.67% accuracy and 7.28% F1 score. A corresponding 8-feature numeric dataset was derived from the kurtosis and skewness of the image histograms in four color channels (red, blue, green and greyscale) produced from each tile provided the dataset for the NN model which has 90.33% accuracy and 19.08% F1 score. Experiments with varying parameters ranging from annotation size, image split size, training dataset ratio, and different label threshold were performed to increase the model performance. By assigning weights to both CNN and NN, an ensemble method with improved results was created and post processing methods were also applied. The final ensemble model yielded a 91.81% accuracy and 42.36% F1 score. The improvement from the baseline CNN is shown to be statistically significant, and this shows that we can create a model to distinguish the damage regions on UAV rice field images caused by typhoons.

- Masters of Science in Computer Science
- Ateneo de Manila University

> Publication on going

## dGrav: Visualizing Data Gravity in a Network

### Abstract
Data gravity is a relatively new concept which suggests that data and other entities(applications and services) in a network exert force on each other. dGrav computes and provides visualization for data gravity to allow users to look for patterns and trends in an application’s behaviour in a network. Using latency, bandwidth, average request per second, average request size, application mass, and data mass, data gravity between an application and its data can be computed. We evaluated dGrav on a LAN with a shared MySQL database server where applications installed on other servers connect to access data. dGrav automatically retrieves and computes the values by executing database queries and run- ning network tools. Computed data gravity values are stored in a log file and then rendered for visualization.

- Bachelor of Science in Computer Science
- University of the Philippines Los Baños
- [Paper](https://jachermocilla.org/publications/eclarin-ncite2014-dgrav.pdf)

```markdown
@inproceedings{eclarin-dgrav-ncite2014,
  author = {Nino R. Eclarin and Joseph Anthony C. Hermocilla},
  title = {dGrav: Visualizing Data Gravity in a Network},
  booktitle = {Proceedings of the 12th National Conference on IT Education (NCITE 2014)},
  year = 2014,
  month = oct,
  publisher = {Philippine Society of Information Technology Educators},
  pages = {142-148},
  pdf = {eclarin-ncite2014-dgrav.pdf}
}
```