# Predicting F1 Qualifying Positions


## Table of Contents

1. [Background](#background)
2. [Dataset](#dataset)
3. [How to Run](#how-to-run)
4. [Team Members](#team-members)


## Background

Qualifying sessions are crucial in deciding the starting positions for races in racing, especially Formula 1 (F1). Numerous elements, such as the driver's skill, team performance, track features, weather, and vehicle specs, affect qualifying results. Predicting qualifying positions with accuracy can help teams, analysts, and fans comprehend the competitive landscape and offer insights into performance trends.

The goal of this project is to develop a machine learning-based ranking system that uses supervised learning techniques to forecast F1 qualifying positions. In particular, we used two cutting-edge ranking algorithms made to optimize for ordinal outcomes: LambdaMART and RankNet:


**LambdaMART** is a gradient-boosting system that modifies gradients in response to variations in pairwise rankings. It works well for learning-to-rank exercises that need ordinal connections between things, like driver ranks.

**RankNet:** A neural network model that learns ranking preferences by minimizing a pairwise loss function. It maximizes pairwise associations between items and interprets ranking scores probabilistically.


## Dataset

**Fast F1** With access to telemetry, lap times, weather, driver performance, and more, the FastF1 dataset is an extensive collection created to make it easier to extract and analyze Formula 1 data. It provides comprehensive insights into racing events by utilizing official F1 time data and the Ergast API, allowing for in-depth analysis of both past and current F1 sessions. Learn more about the Fast F1 dataset [here](https://github.com/theOehrly/Fast-F1)


## How to Run 
**1. Clone the Github Repository**

```
git clone https://github.com/emilyjhuang/F1qualifying.git
```

**2. Change Directory to Cloned Repository**

```
cd /path/to/repo
```


**3. Install Dependecies** 

```
pip install -r requirements.txt
```

**4. Run the code!**

## Team Members
- [Hatim Rehmanjee](https://github.com/Hatimqr)
- [Emily Huang](https://github.com/emilyjhuang)
- [Sudiksha Kalepu](https://github.com/sudikshakalepu)
- Adrian Yan
