# Nice Drawing
This project was inspired by Google’s experiments on Quick, Draw!, an online game where the players are asked to draw objects belonging to a particular object class in less than 20 seconds, and AutoDraw, a drawing tool that pairs machine learning with drawings from artists to help users create drawings easier. Google creates the world’s largest doodling dataset with the game “Quick, Draw!” and has made it publicly available. We would like to leverage the dataset and be part of the community of exploring the application of the state-of-the-art technologies towards visual art and communication. 

In this project, we built a classification engine for doodle drawings of 15 animal categories and constructed a web-based application that recognizes the input of a sketched drawing or a photograph and returns an output of thousands similar looking line drawings.  

+ **Dataset**: The [Quick Draw Dataset](https://github.com/googlecreativelab/quickdraw-dataset) consists of 50 million drawings across 345 categories, contributed by players of the game Quick, Draw!. In this project, we chose 15 animal categories, (i.e., ant, bear, bee, bird, cat, dog, duck, flamingo, frog, octopus, owl, penguin, pig, snail, and tiger) from the whole dataset. The dataset had already been preprocessed to a uniform 28×28 pixel image size from the raw data that also includes the timestamps and the country code.

![](https://ws2.sinaimg.cn/large/006tNbRwly1fyegrd3g0aj30gr0nm0w3.jpg)

+ **Language/Platform**: Python, Java Script, Google Cloud Platform

+ **Analytics Algorithms**: Logistic Regression, CNN, t-SNE
