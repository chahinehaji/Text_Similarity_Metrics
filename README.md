# Text Similarity Metrics

In this post we will discuss and implement some methods for calculating text similarity.

We will start with very well known method called Cosine Similarity method.

## Cosine Similarity
It is a metric used to measure how similar the text documents are. The inception behind this method comes from the math and the measurement of the cosine angle between two vectors after projection in multi dimensional space.


<p align="center">
  <img width="460" height="300" src="res/angle.png" title="Angle between two vectors" >
</p>

In the following example we assume that the two vectors represents two sentences. 
If the two vectors are close to parallel, we can say that the two sentences are similar. But if the two vectors are orthogonal, we will that these two sentences are NOT similar.
<br/>
In cosine similarity the smaller the angle the higher the similarity.
<br/>
Mathematically
<br/>
<p align="center">
  <img src="res/dot.png" title="Angle between two vectors" >
</p>

<p align="center">
  <img src="res/cosine_formula.png" title="Cosine Formula" >
</p>

<p align="center">
  <img src="res/cosine_fomula2.png" title="Cosine Formula" >
</p>
