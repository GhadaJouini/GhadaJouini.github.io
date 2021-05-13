---
title: "The Far Side of AI: Neuro-Symbolic AI"
date: 2020-01-25T08:06:25+06:00
#description: Symbolic AI, Deep Learning, Neuro-Symbolic AI.

---

>  Key Words: Symbolic AI, Deep Learning, Neuro-Symbolic AI

 <iframe src="https://medium.com/media/b89cbc7a97d394fc070563c4394768d5" frameborder=0></iframe>

## Introduction

Artificial Intelligence( AI ) has been witnessing a monumental growth in bridging the gap between the capabilities of humans and machines.

Building thinking machines have been a human obsession for decades. Despite, the current advances in AI and ML, concerns about trust, safety, interpretability, and accountability of AI were raised by influential thinkers. In this article, we will discover the next wave of AI systems by introducing the **Neuro-Symbolic AI approach**.

## Why Deep Learning is not enough?

In recent years Artificial Intelligence, specifically Deep Learning has gained popularity thanks to the availability of computational power and the accessibility to a large amount of data.

Current advances in DL have achieved unprecedented impact across research communities and industries. However, deep learning models are black boxes, meaning that we don’t know what’s happening inside which can lead to a lack of interpretability of the results.
Deep learning algorithms are week when it comes to logical questions and researchers believe that for AI to advance and think like a human brain, it must understand not only the ‘what’ but also the ‘why’ which can give a clarity about the cause-effect relationships that can lead to a better explicability of results.

To better understand this limitation let’s take the following examples:
Say, an AI program is asked to Look at the picture below and tell “I**f there are an equal number of large things and metal spheres?**” or **“What is the shape of the object closest to the large cylinder?”**

![](https://cdn-images-1.medium.com/max/2000/1*n0jazMI97LyhxR5Wfl0biw.png)

Another example: **“How many blocks are on the right of the three-level tower? “**

![](https://cdn-images-1.medium.com/max/2000/1*n5Z-g4DLjcURsrWKZ0d5bA.jpeg)

It turns out that state-of-the-art AI neural network systems irrespective of how much data we give they struggle. This is really interesting for us because these are cases where no matter how much data we have deep learning architectures don’t answer for some reason.
>  **So how can we build machines that can answer these types of questions ??**

Back in 1956 researchers were implementing another kind of AI called the symbolic AI.

## Symbolic AI (Classic Symbolic AI)

Symbolic Artificial Intelligence, also known as Good, Old-Fashioned AI (GOFAI), was the dominant paradigm in the AI community from the post-War era until the late 1980s.
The Symbolic AI uses human-readable symbols that represent real-world
constants (objects / entities) to create ‘rules’ (predicates: relations between constants) for the concrete manipulation of those symbols, leading to a rule-based system.
Let’s take the Simpsons family tree example to understand how symbolic AI works.

![](https://cdn-images-1.medium.com/max/2000/1*LFAXLcrsdXpzp5gDTH947w.jpeg)

The **constants** are people, for example, Abe, Homer, and Lisa, and the **predicates** are the relationship between those people. Using this rule-based paradigm we can infer new relationships between objects that a simple Deep Learning model is incapable of extracting them like Herb is the half-brother of Homer and many more.
>  This is very similar how our brain works.

## **Symbolic** AI benefits

* **Interpretable:** when dealing with real-world data we want to have an explanation of why the algorithm gave us a certain decision (medical areas or law etc)

* **Generalization at concept level through reasoning**

* **well established solvers/planning algorithms**

## Symbolic AI VS Deep Learning

One of the main differences between machine learning and traditional symbolic reasoning is where the learning happens. In machine- and deep-learning, the algorithm learns rules as it establishes correlations between inputs and outputs.

![](https://cdn-images-1.medium.com/max/2000/1*nnxaAyX_2RlbnqTaNLgzJg.jpeg)

In symbolic reasoning, the rules are created through human intervention. That is, to build a symbolic reasoning system, first humans must learn the rules by which two phenomena relate, and then hard-code those relationships into a static program.

![](https://cdn-images-1.medium.com/max/2000/1*a8zeX5fpCFAkwDUu-f6KAA.jpeg)

This is how Deep Neural Networks see a picture of an “Apple” as an Apple, by extracting the patterns at pixel level.

![Source: MIT-IBM Watson AI Lab](https://cdn-images-1.medium.com/max/2000/1*x1EhRlAtm1B7g14Y9syMPA.png)

But symbolic AI sees the apple as a graph of rules: an apple is a fruit, it could be green or red, the shape is round, etc. this sounds pretty cool and this is exactly how our brain works.

![Source: MIT-IBM Watson AI Lab](https://cdn-images-1.medium.com/max/2000/1*nr7sGEOFN67eHu4WujfHwg.png)

## Symbolic AI downsides and the rise of Neuro-Symbolic AI

Symbolic AI sounds much more clever comparing to DL systems and you may wonder why nowadays we’re talking only about Deep Learning applications. A key disadvantage of Symbolic AI is that for the learning process — the rules and knowledge have to be hand-coded which is a hard problem when facing complex real-world situations. For instance, researchers had to explore newer avenues in AI rather than Symbolic AI because they cannot handcraft the entire word problems, and here’s where comes the deep learning mission to automate the handcraft work used to be done manually by humans and together they form what’s called Neuro-Symbolic AI.

## Neuro-Symbolic AI: Getting AI to reason

Neuro-symbolic AI is a unison of Deep Neural Networks and Symbolic AI techniques, it is a combination of learning and logic. On the one hand, deep learning is responsible for capturing complex correlations in massive datasets, and on the other hand, Symbolic models have a complementary strength in capturing compositional and causal structure. The unification of the two approaches would address the shortcomings of each.

![](https://cdn-images-1.medium.com/max/2000/1*YdE7SNjeHLQnNKt_4kRCEQ.jpeg)
>  Neuro-Symbolic [AI] models will allow us to build AI systems that capture compositionality, causality, and complex correlations,” — **Brenden Lake**.
>  Neural networks help in getting answers from the messiness of the real-world data to a symbolic representation of the world, constituting correlations in images. Together, they can do some pretty magical things in reasoning. — **David Cox**, Director of MIT-IBM Watson AI Lab.

## **Advantages of Neuro-Symbolic AI**

* **Higher Accuracy.**

* **Data Efficiency:** The biggest problem with deploying neural networks in the real world is that we rarely have big data. Experiences have proved that working with Neuro-Symbolic AI can do better than most of the end-to-end train systems. it requires fewer training examples and can perform higher accuracy.

* **Transparency and Interpretability:** we need to understand why the decision is made otherwise we can’t trust the AI system. and this is exactly what Neuro-Symbolic AI does, it takes a decision that we can understand the rules of it.
>  **👌 With Artificial Intelligence we are summoning the demon — Elon Musk**

## Conclusion

In order to imitate human learning, scientists and researchers working to develop models of how humans represent the world and frameworks to define logic and thought. Neuro-Symbolic AI contributes towards the development of explainable and accountable AI and machine learning-based systems and tools.

![](https://cdn-images-1.medium.com/max/2136/1*vCjSishwUqFm8Yh348keEQ.jpeg)

## 💥 Happy Reading Everyone !

## References

[https://www.youtube.com/watch?](https://www.youtube.com/watch?v=4PuuziOgSU4&ab_channel=AlexanderAmini)

[CogX 2018 — Symbolic Methods Coming Back | CogX — YouTube](https://www.youtube.com/watch?v=r8ZlKx2d2dA&ab_channel=CogX)

[v=4PuuziOgSU4&ab_channel=AlexanderAmini](https://www.youtube.com/watch?v=4PuuziOgSU4&ab_channel=AlexanderAmini)

[Getting AI to Reason: Using Neuro-Symbolic AI for Knowledge-Based Question Answering | IBM Research Blog](https://www.ibm.com/blogs/research/2020/12/ai-neurosymbolic-common-sense/)
