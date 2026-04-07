# Official Code for Attentive Moment Retrieval in Videos


## Introduction
In the past few years, language-based video retrieval has attracted a lot of attention. However, as a natural extension, localizing the specific video moments within a video given a description query is seldom explored. 
Although these two tasks look similar, the latter is more challenging due to two main reasons: 1) The former task only needs to judge whether the query occurs in a video and returns an entire video, 
but the latter is expected to judge which moment within a video matches the query and accurately returns the start and end points of the moment.  Due to the fact that different moments in a video have varying durations and diverse spatial-temporal characteristics, uncovering the underlying moments is highly challenging. 
2) As for the key component of relevance estimation, the former usually embeds a video and the query into a common space to compute the relevance score. 
However, the latter task concerns moment localization, where not only the features of a specific moment matter, but the context information of the moment also contributes a lot. 
For example, the queries may contain temporal constraint words, such as ''first'', therefore need temporal context to properly comprehend them. To address these issues, we develop an Attentive Cross-Modal Retrieval Network.

## Links

- **Paper**: [ACM SIGIR](https://arxiv.org/abs/xxxx.xxxxx)
- **Code Download**: [Baidu Netdisk](https://pan.baidu.com/s/1eUgvASi)

We also reimplemented the code for several baseline methods:
- **Code Download**: [MCN](https://github.com/LisaAnne/LocalizingMoments)
- **Code Download**: [Glove](https://pan.baidu.com/s/1htqQDla)
- **Code Download**: [TALL](https://github.com/jiyanggao/TALL)
- **Code Download**: [TALL](https://pan.baidu.com/s/1kWjsXYB)
- **Code Download**: [VSA-STV](https://pan.baidu.com/s/1eTX8hOI)
- **Code Download**: [VSA-RNN](https://pan.baidu.com/s/1mjx4eve)
  
## Method Overview

<p align="center">
  <img src="./framework.jpg" alt="framework" width="75%">
</p>


## Results

<p align="center">
  <img src="./results.jpg" alt="results" width="85%">
</p>

Our method achieves competitive or superior results compared with previous methods on multiple benchmarks.

