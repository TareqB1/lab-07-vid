[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/oKs9cMRq)

![example workflow](https://github.com/cpit252/lab-7-TareqB1/actions/workflows/classroom.yml/badge.svg)

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/TareqB1/lab-07-vid/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/TareqB1/lab-07-vid/tree/main)

[![codecov](https://codecov.io/gh/TareqB1/lab-07-vid/branch/main/graph/badge.svg?token=WFBZRJYI9K)](https://codecov.io/gh/TareqB1/lab-07-vid)




Q2: Change the number of created images to hundreds of thousands to experiment with the effects of the flyweight pattern? How many flyweights have been created??

Ans: Changing it to 20000 will result in 4 flyweights
     Changing it to hundred thousand will also result in 4 flyweights.

----------=--------------=------------=------------=--------------=---------------=-------------=-------------=--------------

Q3: Explain how the flyweight design pattern reduces the number of objects stored in memory compared to storing all objects in memory??

Ans:    The Flyweight pattern suggests that you stop storing the extrinsic state inside the object. 
        Instead, you should pass this state to specific methods which rely on it.
        Only the intrinsic state stays within the object, letting you reuse it in different contexts.
        As a result, you’d need fewer of these objects.
