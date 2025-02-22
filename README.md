<img align="left" src="videos/adm.jpg" width="50%" height="50%" alt="hengshuai yao" HSPACE="40" VSPACE="40" class="inline"/>

Hi, my name is Hengshuai Yao. I like to work with full passion, but remind myself to relax.  

My research inspired [Gradient TD](https://proceedings.neurips.cc/paper/2008/file/e0c641195b27425bb056ac56f8953d24-Paper.pdf) (Sutton et. al., 2008), [GTD2 and TDC](https://icml.cc/Conferences/2009/papers/546.pdf) (Sutton et. al., 2009). GTD and GTD2/TDC were widely acknowledged to start an important class of off-policy learning algorithms. 

I appreciate Dimitri Bertsekas, Lihong Li, Huizhen Yu and a few others for crediting my work in providing a new perspective for TD-based policy evaluation algorithms. My preconditioning paper should have been credited by the off-policy learning literature for the source of Gradient descent-based TD ideas as well. If you work on GTD and TDC, I appreciate you citing my work. 

[Impression GTD](https://arxiv.org/abs/2307.15892) 

[Baird's counterexample is solved.](https://arxiv.org/abs/2308.09732)

<!-- 
Unfortunately, these three works were not independent. We had a phone conversation (for interviewing me as a Ph.D candidate in March 2008) and lots of email discussions before their NIPS 2008 submssion. I did experiments for GTD and compared GTD with TD. I wrote a two-page PDF, in which I pointed out (1) two time-scale formulation of GTD is slow; (2) the two step-sizes are not easy to use. Read the conclusion of the GTD paper to have a sense of the tone change from "ground breaking" to "practicality". Someone also asked me to send the Boyan chain code to his other student. Later on, the TDC paper's Boyan chain experiment was based on my code. In my experiment, I used **on-policy problems** to study the convergence rate of **off-policy learning algorithms**. This was the first time in literature to use this experimentation method (e.g., read the importance sampling off-policy TD papers By [Sutton, et. al. in 2000](http://incompleteideas.net/papers/PSD-01.pdf) and [2001](http://www.incompleteideas.net/papers/PSS-00-original.pdf) to see their experimentation method). This experimentation method was adopted in **all** the experiments of the TDC paper, including the GO experiment performed by David Silver who joined the paper development after me. Later, our literature (e.g., see [TDRC](https://arxiv.org/pdf/2007.00611.pdf)) uses this method as a standard way to study off-policy learning algorithms. When I used this experimentation method in 2008, the motivation was that, Okay, "off-policy" learning algorithms... If they cannot learn "on-policy", it's meaningless. This is the basic functionality test that off-policy learning has to pass.  

I had wished for the authors of the GTD, TDC/GTD2 papers to have a reflection (e.g., search  the email boxes?) on (1) whether the GTD and TDC papers took great advantage of the preconditioning paper without giving any credit, and (2) whether my involvement at the time deserved the authorship. I patiently waited I guess. Is 15 years still not enough for someone to rethink about it? There hasn't been a single kind gesture from someone who did this. How many 15 years do we have? and in research career?

I was also involved in the GTD discussions and a part of the TDC paper development. However, for some reason my name was not there. I wish the GTD and the GTD2/TDC authors can read [my preconditioning TD paper](papers/ptd.pdf) and [compare with yours](gtd_novelty.md). Authors of these two papers please kindly have a reflection (e.g., search  your email boxes) on, **(1) whether the GTD and TDC papers took great advantage of the preconditioning paper without giving any credit; (2) whether my involvement at the time deserved the authorship**. Some of the authors agreed to give future credits when they will write on the topic. 

This has been about 15 years, for which I had somehow waited for some sort of remedy. This has confused me for a long time throughout my Ph.D time and career choice. It's about just another 15 years for my left career. I have a family too. Occasionally, I also wrote on the off-policy learning topic. I refrained to discuss this even though there is relevance of discussion. None of my coauthors knew about it. In a small literature, some people knew my work. Out wild, people just judge your research by looking at your citations.  

-->

## Research Interests
My interest is mostly **model-based reinforcement learning**, and **step-size adaptation**. Interesting thing is a connection between the two seemingly unrelated topics. The "learning to accelerate" paper below has the details. I really like this work. I consider it is the best work out from me in my twenty years of research since I started.  

Understanding deep neural networks is my recent interest. Deep learning was not my area. I became interested in it mostly because of the deep reinforcement learning. I took a look at the literature for about three years. Some problems, which seem quite fundamental, remain poorly understood or unsolved. This aroused my curiosity. The work on class interference, decision boundary and step-size planning summarize my readings and thinking in this regard.  

I worked on multi-step linear Dyna-style planning, model-based approximate policy iteration, and a reinforcement learning perspective for PageRank. I explored reinforcement learning for NCSoft game studio in San Francisco. I was the founding PM of a few joint lab projects between University of Alberta and Huawei Technologies Canada. I have mentored 20 graduate students from UofA. I was an adjunct professor at Department of Computing Science, University of Alberta. 

[My google scholar](https://scholar.google.ca/citations?user=R_wcnUgAAAAJ&hl=en)  

## Lifelong Acknowledgement 
I deeply appreciate the help from Csaba and Dale in my hard time.  Their minds have helped me to think clearly who am I and what I'm best at. They always encourage me to pursue science, and focus on the positiveness of life and research. I appreciate Randy Goebel for supporting me in the past two years.

I also appreciate the author of Temporal Difference learning, linear Dyna and IDBD, Dr. Richard S. Sutton, at heart. His TD paper stimulated the first interests in a baby student. I was following some reference in the world Robocup simulation community and found TD. His linear Dyna is still influencing my mind today. I greatly appreciate his acceptance of me as a Ph.D student. 

I'm greatly thankful to Andy Barto. Andy is so kind. When I struggled with the interests on TD and had great trouble in publishing the preconditioning idea, he and his student George Konidaris helped me improve the paper greatly. He also recommended me to come to UofA for studies even though he never met me in person before.       

My supervisor at Tsinghua University, Zengqi Sun, alway supported me for my exploration reinforcement learning. He already retired but I always remember during Robocup 2004 in Portugal, I just briefly mentioned there was something not clear to me in Simon Haykin's neural networks: a comprehensive foundamentation book. He told me just to come to his hotel room and he will explain to me. He did.    

<!-- 
## My philosophy of being a reviewer and being reviewed 
Yes, sometimes I am a harsh reviewer too. Generally, I am either a friendly (accept or reject) or a harsh (reject) reviewer. I'm in a harsh mode if I found the paper being reviewed overclaims with either insufficient literature review (reinventing things) or poor evidence supports. 

I think it's Okay to be harsh. **Just please always back up our claims/criticism with evidence** (from where we think there is something wrong with the paper being reviewed, or something that has been done in the literature). 

As an author, I am only annoyed when receiving reviews like "I don't find anything that is good in this paper", without any backup. "The motivation of this paper is not clear", without explaining why, which was confusing because the title and abstract only are very clear about this. One reviewer also asked "why do you study exploration?" (for a reinforcement learning paper), without giving the reason for asking this question. Recently, I have all reviews like this. Had I written a review like the first two, I will back up with: 

- The first idea in the paper is not good because ... (either it is not sound or it has been done) 
- The algorithm and experiments performed in the paper are not good because ... (either the algorithm is not novel, or experiments were done in a poor manner; e.g., hyper-parameter choices were not well described, or empirical results were not well interpretted; etc. 
- The motivation is not clear because it is hard to understand ---**Don't forget to explain here**--- e.g., I have difficulty in understanding the concept of "ABC", or the mathematics like equations 1 to 3; etc. I'm always willing to show that I'm dumb in understanding things, because all the authors I reviewed have been very happy to teach me things, as long as I'm giving the specifics. More often than anything, I saw reviews like "the paper is hard to understand" without explanations. It leaves lots of questions for the authors, like, what parts create the difficulty to understand? Without giving explanations, the authors may doubt, which parts of the paper did the reviewer actually read, and how many minutes were spent in reading? It leaves confusion and no room for anyone to learn.    

**Giving specifics in reviews creates opportunities for the authors and the reviewers to communicate ideas and learn from each other**. Without backups, the reviews, even though they can be true, the way they are written, do no good to anybody nor our literature except negative feelings about our research and the community. 

Criticize when we're sure. With evidence. I've seen in literature people have similar frustrations. I think most of us authors are fine of being criticized. The research community is a very open minded group in general. 

This may sound a bit negative, but I really wanna to say this aloud, because I think this is our problem: **As a reviwer, we should be more careful than what is being carried out in literature now: Writing reviews with un-backed up criticism is an insult to the authors** (even if it wasn't meant to). Surely we can tell the authors "don't take it personally." Perhaps, we should be more careful in not emitting the negatiness to authors and ask them to take it positively on their sides? Superficial and unsupported criticism is in fact against the spirit of science. 

Science is not polictics. Science is based on facts, either mathematics or experiments that can be used as facts. Talking in the mind that "I don't like your paper" with a professional tone however don't give backups/facts in reviewing papers is the biggest challenge of our review system. It's Okay that you don't like a paper. **Just please reject nice, reject with a friendly tone (if you can, give hard technical anti-facts; all authors will appreciate and look up to your endeavours and knowledge), tell the authors why, and our reasoning** because it is our responsibility as a reviewer. If we are a reviewer, we are not an ordinary reader.     

I strongly agree readers have different backgrounds and take in different information. **Just please read the paper for more than 10 minutes before starting writing reviews**. Please. Thanks. For the dream of our AI. For someone who is as serious as you in pushing the goals of AI.   

## Could this be a risk for AI literature?
I don't know if anyone has the same observation and concern with me. I recently submitted to a conference that I never did. The conference is a top and famous one. By accident, after submission, I found someone has 20+ papers in this conference, a single year. This guy also serves an important position at this conference and community. Some of this author's paper are also on arxiv. A few years ago, I also saw some famous author had 13+ papers on ICRA, one year. It is not uncommon these days. Here is the reality of our AI literature: "fame/positions + lab/network scale + arxiv + this review process". 

You don't see this implicit bias in play. Someone serves as the area chair for your paper and this famous author. Both of the papers receive similar scores (both borderline). The AC of course knows this famous author. The AC buzzes the reviewers of this author's paper: Hey, guys, I read your reviews. R1 said something strong about this paper. Could R2 and R3 take a look? R2 and R3 at this stage, are very likely to search and find whether the paper is on arxiv (maybe they have done so before doing reviews). If so, what do you think they will think and what will they do? The AC just didn't do anything about your paper. It is mostly likely a silence even if your rebuttal points out critical problems in the reviewer. I've seen this a few times in my role of being a reviewer (for both kinds of papers). Eventualy, the other one was accepted. Your paper got rejected. This poor "you" are mostly likely a new student or a researcher just into this area, who has no name or not much fame, and possibly just submits one paper and perhaps all by himself/herself.  

I think our literature should rethink whether 20+ or 30+ papers in a single conference (one year!) is a good thing to do or not. Obviously some of these guys are leaders of our community. We follow you. We cite you. We hope you create and improve our publication and review system. 

What kind of contributions could one make across 30 (50?) submissions, with the same deadline? How is that possible to make sure the literature review is sufficient and results (theorems and experiments) are all correct to support valid claims?  In the extreme case, how does one make sure, across this many submissions, none of them takes advantage of other people's work (published and unpulished on arxiv)?

I'm far from someone who can tell this. However, as a middle-aged researcher, I'm really worried about this. I've reviewed so many DRL papers that either reinvent well-known algorithms (sometimes without citing the results in reinforcement learning), or doing empirical works with neural networks without asking interesting questions and not much thinking; etc. If everyone aims to publish **as many papers** and maximize one's impact like this (hopefully not in whatever ways), without aiming to solve a core of fundamental problems and spending years of investigation into relevant literature, the **real AI research** is going to be killed by ourselves.

The review process of an AI paper is like running a deep model. Putting papers on arxiv before submission initializes the model with a different bias. In training the model (reviewing process), reviewers and ACs are both forming the decision boundary, and **regularized** by the bias. Though many researchers put on arxiv, the purposes may be different. 

If you've played this prisoner dilemma (multiple times of submissions) before, the worst result of not arxiving is your idea being stolen (not by text percentage wise, which is easy to detect, but the key stuff in your paper being taken by someone: experiments and derivation, e.g., are done in a different way, etc.). Instead, by putting on arxiv, the worst result is being rejected and you still have your idea recorded in public. Given the huge number of papers accepted for famous authors, it's a reasonable question what are their acceptance rates, and do they have the same motivation with us in putting on arxiv? Who dares to steal ideas from famous authors? Stealing is not allowed for anyone in research btw. My point is not that "who should dare to steal from what". However, the damage to someone who is plagiarized and not famous is way more bigger. In case a famous author got plagiarized, the damage caused is little: the author's career and position won't perhaps be influenced much. 

Finally, to explain why I ask this question: I've read many good and seminal papers by famous people. However, it is also not uncommon to be diappointed by reading some papers from some famous guys who publish so much.           

-->

---

### Publication

- [The Vanishing Decision Boundary Complexity and the Strong First Component](http://arxiv.org/abs/2211.16209). Hengshuai Yao. arXiv:2211.16209. 2022. 

Why do we study the decision boundary? It is an important concept widely used to understand the generalization of machine learning classifiers. For example, it is well known that overfitting leads to complex decision boundaries, e.g., see [this illustration](https://en.wikipedia.org/wiki/Overfitting#/media/File:Overfitting.svg). Usually in machine learning, by comparing the complexity of the decision boundaries of classifiers (on training set), we can predict the order of their generalization performance (on test set). Is that also true for deep learning? This is the motivation of the paper. 

We show that for deep learning, this level of complexity in the decision boundary does NOT even exist for well trained deep models. For example, models trained by SGD with learning rate annealing achieves 100% training accuracy in the end (overfitting). However, for all class pairs, the decision boundary is linear --- it is not complex at all. Imagine a polynomial based machine learning classifier: how much high order of the polynomial needs to be for 100% training accuracy, and how skewed the boundary will be. However, **the well trained overfitting deep models have a linear decision boundary**.  See the first plot in the following figure, in which the two classes can be split by a straight line in the PCA space:  

<div align="center">
<img align="center" src="videos/pca2_cat_dog.png" alt="hi" class="inline"/>
</div>

Clearly, this shows that deep learning is different from machine learning in this regard. **The knowledge that we transfer from machine learning about the decision boundary complexity vs. generalization does not work for deep learning**. 

Nonetheless, we found that the **decision boundaries of the predecessor models** (immature models in training that are close to the final) are indicative of the final model's generalization. For example, using the 99.87% model, the boundaries of class pairs can be plotted:
<div align="center">
<img align="center" src="videos/pca2_cat_vs_others.png" alt="hi" class="inline"/>
</div>
The complexity of the boundaries is largely consistent with the generalization errors between the class pairs (see our Class Interference paper below). 


We make a few videos for the decision boundary evolution, and study the effects of architectures and optimizers. 

CAT(always blue)-PLANE decision boundary evolution in training:
<div align="center">
<iframe width="678" height="381" src="https://www.youtube.com/embed/-jnh5Bo9sTQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

CAT-DOG:
<div align="center">
<iframe width="678" height="381" src="https://www.youtube.com/embed/OA7fCDpL5Rc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

You can see that the CAT-DOG boundary clears around 191st epoch, which is slower than CAT-PLANE (around 180th epoch). This is because CAT and DOG are more similar classes and they interfere in training. Also note that the splitting of the two classes in the videos happens mainly in the x-axis, which is the first principle component.   

The above is VGG19. Let's see ResNet18 now. 

CAT-PLANE:

<div align="center">
<iframe width="678" height="381" src="https://www.youtube.com/embed/Ks93drvvEDE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

CAT-DOG:
<div align="center">
<iframe width="678" height="381" src="https://www.youtube.com/embed/jH3EGZM2mWI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

Do you notice the shapes of the class clusters are different from VGG19? For ResNet18, the CAT and DOG clusters are much more round, and more self-compact in the end. 

The above is for the SGD optimizer (with learning rate annealing). What about the Adam optimizer? First of all, we found that SGD with learning rate annealing generalizes better than Adam. We wanted to understand this via the decision boundary. 

CAT-DOG, Adam(for VGG19):

<div align="center">
<iframe width="678" height="381" src="https://www.youtube.com/embed/BEIRoP2dBIo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

CAT-DOG, Adam(for ResNet18):

<div align="center">
<iframe width="678" height="381" src="https://www.youtube.com/embed/21MpKOnlF98" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

Comparing with the SGD case, you can find that Adam's decision boundaries are very different: the clusters has a long and thin shape, spanning in a wider range (this means the clusters are more loose). Also, the classes are not well split in the PCA space. 

Why in the above videos, the splitting behaviors most happen along the x-axis (1st principle component)? The following picture shows that the strength of the first principle component grows stronger and stronger in training, so much so that in the end it supports 100% training accuracy all by itself (this is shown by all the SGD videos). 

<div align="center">
<img align="center" src="videos/strength_1st_component.png" alt="hi" class="inline"/>
</div>
Our results show that **the strength of the first component is strongly correlated with generalization**. For example, the above plot shows that VGG19's first singular value is much larger than the better-generalizing ResNet18 and DLA. The paper has a detailed studies on the spectral profiling of the auto-correlation vs. the generalization performance for ten deep learning optimizers as well as the effects of the skip connections. 

---

- [Class Interference of Deep Neural Networks](https://arxiv.org/abs/2211.01370). Dongcui Diao, Hengshuai Yao, Bei Jiang, arXiv:2211.01370. 2022. 

**What is the bottleneck for deep learning**? For example, on CIFAR-10, VGG19 achieves about 93.5% test accuracy, and ResNet18 achieves about 95.2%. Why is that and what can we learn about their generalization performances, and why does ResNet18 generalize better? 

This paper starts with a metric called **CCTM** (cross-class test map) that combines the *true positve rates* (diagonal) and *false positive rates* (off-diagonal) into a single square matrix. This figure and table compare the two models using the CCTM heatmap plots for intuitive visualization:

<div align="center">
<img align="center" src="videos/cctm.png" alt="hi" class="inline"/>
</div>

This simply shows that CAT and DOG have much bigger generalization errors than the other classes. This phenomenon is observed for all the models and all the optimizers we tried. For example, ResNet50 has a similar test accuracy to ResNet18 with SGD+learning rate annealling. 

We call this phenomenon **class interference**. It is the biggest source of generalization errors in deep learning. ResNet18 handles intereference better than VGG19, especially for class pairs like CAT-DOG, CAR-TRUCK, PLANE-SHIP and CAT-FROG. 

The CCTM above also shows there is a **symmetry** in class interference. For example, the interference from CAT to DOG is similar to the other way around. 

Interestingly, the next plot (using the training set) shows that this is not incidental: the two errors are related! The cats in the training set are frequently predicted as DOG; vice versa. This means these two classes interefere with each other. 

<div align="center">
<img align="center" src="videos/cat_dog_dance.png" width="100%" height="100%"  alt="hi" class="inline"/>
</div>

Read the paper for details and see the interference between CAR and TRUCK, and CAT and FROG, and our finding for the extremely sharp minima for SGD with small learning rates/step-sizes, and the extremely flat minima located in large terrains for SGD with annealled learning rates. 

Thus our conclusion is, **the class interference is the bottleneck of deep learning**. It represents the learning difficulty regarding similar classes in the data. This is a challenging task for human beings as well. Eyeing cross images samples in CIFAR-10, we found some cats are even hard to tell apart from DOG. 


---

- [The Sufficiency of Off-policyness: PPO is still insufficient according to an Off-policy Measure](https://arxiv.org/pdf/2205.10047.pdf). Xing Chen, Dongcui Diao, Hechang Chen, Hengshuai Yao, Jielong Yang, Haiyin Piao, Zhixiao Sun, Randy Goebel, Bei Jiang and Yi Chang. AAAI, 2023. 

This year AAAI has 8777 submissions. The number of *accepted papers* is 1721, similar to the number of *submissions* around 2008. AI is insanely growing. 

This paper has an interesting observation: The famous PPO algorithm fails to discover better policies that is beyond the clip range of the importance sampling ratio. In particular, the figure below shows better policies can deviate as much as 20 to 60 times from the policy in last iteration! The [1-epsilon, 1+epsilon] clipping range for the importance sampling ratio by PPO is way too small. If one increases epsilon for PPO, it becomes worse and unstable in performance because of the gradient variances. Our P3O is a solution to tame the importance sampling ratio in an interesting way: in theory it allows the importance sampling ratio to go very large while maintaining low gradient variances and stability of the algorithm. We also have an interesting interpretation of our method being an exploration method for continuous (-state and -action) reinforcement learning, for which counting based methods such as UCB do not apply.  

<div align="center">
<img align="center" src="videos/deon_ppo_p3o.png" alt="hi" class="inline"/>
</div>


There is a recent interesting paper [You May Not Need Ratio Clipping in PPO, 2022](https://arxiv.org/pdf/2202.00079.pdf) by Sun et. al. that also challenges the clipping operation of PPO, which is inherited by many literature improvements of PPO. The "May Not Need" paper has an observation that the ratio clipping may not be a good option as it can fail to effectively bound the ratios. Their empirical results show that the ratios can easily depart from the range
[0.5, 2.0]. Our paper is more focused on understanding the benefits of allowing the ratios to be very large and why it makes sense to do so. Their paper explores directly optimizing the CPI objective but for stability consideration, they apply early stopping for the optimization process once the ratio goes beyond a threshold. My interpretation of their method is that it is a dynamic clipping method (need to read in more details). Both their method and ours show that removing the ad-hoc clipping can greatly improve the performance of policy gradient methods.  

---

- [Learning to Accelerate by the Methods of Step-size Planning](https://arxiv.org/abs/2204.01705). Hengshuai Yao. arXiv:2204.01705. 2022. 

In this paper, I discussed 
<ul>
   <li> a data perspective for gradient descent, and the possibility of using the gradient descent update data to learn and plan step-sizes for an acceleration of gradient descent. </li>
   <li> a new understanding of individual step-sizes for parameters, that the collection of them, in the form of diagonal matrix as we explored in the paper, can be viewed as a multi-step transition model for gradient descent update. </li>
   <li> the diagonal-matrix step-size has the same projection power as a full-sized matrix. Why is this important? The difference is O(n) or O(n^2). The difference is whether O(n) can be exact. This frees the diagonal-step-size from approximating Hessian. </li>
   <li> why negative step-sizes make sense for both deterministic and stochastic settings for fast convergence. </li>
 </ul>

All the above four ideas can be understood from this figure in the paper. 
<div align="center">
<img align="center" src="videos/csawg_illustration.png" alt="hi" class="inline"/>
</div>

Beneficial readings: [GD for high-d problems and step-size halving (1944)](papers/step_size_curry1944.pdf), [Line search (1966)](https://msp.org/pjm/1966/16-1/pjm-v16-n1-p01-p.pdf), [vectorized step-size and meta-gradient by IDBD (1992)](https://www.aaai.org/Papers/AAAI/1992/AAAI92-027.pdf), [Linear Dyna (2008)](https://arxiv.org/pdf/1206.3285.pdf), [Multi-step Dyna (2009)](https://proceedings.neurips.cc/paper/2009/file/c52f1bd66cc19d05628bd8bf27af3ad6-Paper.pdf), [Hyper-gradient descent (2017)](https://arxiv.org/pdf/1703.04782v1.pdf?source=post_page---------------------------), [Stochastic Polyak step-size (2021)](https://arxiv.org/pdf/2002.10542.pdf), [Nesterov accelerated gradient (English translation, 1983)](papers/nesterov83.pdf), [Polyak (1964)](papers/polyak64.pdf), [First-order meta-learning (2018)](https://arxiv.org/pdf/1803.02999.pdf), [Nesterov course (2003)](papers/nesterov03.pdf), [Black-box first-order methods (1983)](papers/blackbox83.pdf)

---

- [Understanding and Mitigating the Limitations of Prioritized Replay](https://openreview.net/pdf?id=HBlNGvIicg9). Yangchen Pan, Jincheng Mei, Amir-massoud Farahmand, Martha White, Hengshuai Yao, Mohsen Rohani and Jun Luo. UAI, 2022. 

- [Exploring Neural Architecture Search Space via Deep Deterministic Sampling](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9503404). Keith G. Mills, Mohhamad Salameh, Di Niu, Fred X. Han, Seyed Rezaei, Hengshuai Yao, and Shangling Jui. IEEE Access, pp 110962-110974, volume 9 2021. 

- [Breaking the Deadly Triad with a Target Network](https://arxiv.org/abs/2101.08862). Shangtong Zhang, Hengshuai Yao, and Shimon Whiteson, ICML, 2021.

- [Provably Convergent Two-Timescale Off-Policy Actor-Critic with Function Approximation](https://arxiv.org/abs/1911.04384). Shangtong Zhang, Bo Liu, Hengshuai Yao, and Shimon Whiteson, ICML, 2020.

- [Weakly Guided Few-shot Object Segmentation using Co-Attention with Visual and Semantic Inputs](https://arxiv.org/abs/2001.09540). Mennatullah Siam, Naren Doraiswamy, Boris N. Oreshkin, Hengshuai Yao, and Martin Jagersand, IJCAI, 2020.

- [Mapless Navigation among Dynamics with Social-safety-awareness: a reinforcement learning approach from 2D laser scans](https://arxiv.org/abs/1911.03074). Jun Jin, Nhat M. Nguyen, Nazmus Sakib, Daniel Graves, Hengshuai Yao, Martin Jagersand, ICRA, 2020, Paris, France. 

<div align="center">
<iframe width="678" height="381" src="https://www.youtube.com/embed/SJYDiNjwYSQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

- [Hill-climbing on Value Estimates for Search-control in Dyna](https://webdocs.cs.ualberta.ca/~whitem/publications/pan2019hill.pdf). Yangchen Pan, Hengshuai Yao, Amir Masoud Farahmand, and Martha White. IJCAI. Macau, China, 2019.  

---

- [Distributional Reinforcement Learning for Efficient Exploration](https://arxiv.org/abs/1905.06125). Borislav Mavrin, Shangtong Zhang, Hengshuai Yao, Linglong Kong, Kaiwen Wu and Yaoliang Yu. ICML, Long Beach, USA. 2019.

One cool thing about deep RL is the theory of distributional RL. However, why do we need to learn a distribution of the value function at all? While the theory of distributional RL is beautiful, it does not answer this question (yet). For example, in QR-DQN, the paradox is that Q(s,a) is finally taken as a weighted average of the quantile Q values. This weighted average appears to be according to a distribution of the quantiles (In C51, the quantile locations are fixed and the weights/probabilities are learned, while in QR-DQN the locations are learned and the probabilities are fixed). In either case, the Q(s,a) is an estimation of the mean of the return. As a result, ditributional RL (C51 and QR-DQN) still selects actions according to the mean-of-return based value function. This reduces distributional RL to a special method of estimating the value function, back to the standard RL. In my opinion, this loses the point of distributional RL. This paper has an interesting use of the learned value function distribution, in particular, for efficient exploration based on the confidence interval computed from the distribution. Here is the testing performance of this new exploration method (DLTV) in CARLA. This leads to more efficient exploration and even much faster learning than QR-DQN, which motivates "Distributional Reinforcement Learning". 

Relevant papers: [Optimistic Actor-Critic (2019)](https://arxiv.org/pdf/1910.12807.pdf), [Quota (2019)](https://arxiv.org/pdf/1811.02073.pdf), [Non-crossing quantiles (2020)](https://proceedings.neurips.cc/paper/2020/file/b6f8dc086b2d60c5856e4ff517060392-Paper.pdf), [Being Optimistic to Be Conservative (2020)](https://arxiv.org/pdf/1911.01546.pdf), [Truncated Quantile Critics (2020)](http://proceedings.mlr.press/v119/kuznetsov20a/kuznetsov20a.pdf), [TOP-TD3 (2021)](https://proceedings.neurips.cc/paper/2021/hash/6abcc8f24321d1eb8c95855eab78ee95-Abstract.html), [QR-Soft-actor-critic (2021)](https://www.nature.com/articles/s41586-021-04357-7), [Non-decreasing Quantile (2021)](https://arxiv.org/pdf/2105.06696.pdf)

<div align="center">
<img align="center" src="videos/carla_dltv.png" alt="hi" class="inline"/>
</div>

---

- [Deep Reinforcement Learning with Decorrelation](https://arxiv.org/abs/1903.07765). Borislav Mavrin, Hengshuai Yao, and Linglong Kong, 2019. 

<div align="center">
<img align="center" src="videos/dqn_decor.png" alt="hi" class="inline"/>
</div>

- [Reinforcing Classical Planning for Adversary Driving Scenarios](papers/iros_final.pdf). Nazmus Sakib, Hengshuai Yao, Hong Zhang. Preprint, March 2019. Video:

<div align="center">
<iframe align= "middle" width="750" height="400" src="https://www.youtube.com/embed/9BFYX1WRjtA" frameborder="0" allowfullscreen></iframe>
</div>

- [Exploration in the face of Parametric and Intrinsic Uncertainties](papers/dltv_aamas19.pdf). Borislav Mavrin, Shangtong Zhang, Hengshuai Yao, Linglong Kong. AAMAS (poster), Montreal, Canada. 2019.

- [ACE: An Actor Ensemble Algorithm for Continuous Control with Tree Search](https://arxiv.org/abs/1811.02696). Shangtong Zhang, Hao Chen, Hengshuai Yao. AAAI, Honolulu, 2019. (acceptance rate 16.2%)

- [QUOTA: The Quantile Option Architecture for Reinforcement Learning](https://arxiv.org/abs/1811.02073). Shangtong Zhang, Borislav Mavrin, Linglong Kong, Bo Liu, Hengshuai Yao. AAAI (Oral presentation), Honolulu, 2019.

- [Negative Log Likelihood Ratio Loss for Deep Neural Network Classification](https://arxiv.org/pdf/1804.10690.pdf). Future Technologies Conference. Hengshuai Yao, Donglai Zhu, Bei Jiang, Peng Yu, San Francisco, USA. 2019.

- [Towards Comprehensive Maneuver Decisions for Lane Change Using Reinforcement Learning](https://openreview.net/forum?id=SJe9yugRcm). Chen, C., Qian, J., Yao, H., Luo, J., Zhang, H., and Liu., W. NIPS Workshop on Machine Learning for Intelligent Transportation Systems (MLITS). 2018. 

- [Monte-Carlo Tree Search vs. Model-Predictive Controller: A Track-Following Example](https://openreview.net/forum?id=SyiF5-23Z&noteId=S1y46fu1M).  NIPS Workshop on Machine Learning for Intelligent Transportation Systems (MLITS), Yao, H., Nasrati, M., Rezaee, K. Long Beach, USA. 2017. Video:

<div align="center">
<iframe align="center" width="630" height="474" src="https://www.youtube.com/embed/YP7qPJSJAVU" frameborder="0" allowfullscreen></iframe>
</div>

- [Practical Issues of Action-conditioned Next Image Prediction](https://arxiv.org/abs/1802.02975). Zhu, D., Chen,H., Yao, H., Nosrati, M., Yadmellat, P., Zhang, Y. IEEE International Conference on Intelligent Transportation Systems (ITSC), 2018.


- [Pseudo-MDPs and Factored Linear Action Models](papers/pmdp.pdf). Yao, H., Szepesvari, Cs., Pires, B. A., and Zhang, X. IEEE Symposium on Adaptive Dynamic Programming and Reinforcement Learning (IEEE ADPRL), Best student paper nomination, Orlando, Florida, USA, 2014. 

- [Universal Option Models](papers/uom.pdf). Yao, H., Szepesvari, Cs., Sutton, R., and Bhatnagar,S. 2014. NIPS. Montreal, Quebec, Canada. 

Recent communication from Csaba: I thought you may be interested in [this paper](https://proceedings.neurips.cc/paper/2021/file/003dd617c12d444ff9c80f717c3fa982-Paper.pdf): Touati, A., and Y. Ollivier. 2021. “Learning One Representation to Optimize All Rewards.” Advances in Neural Information Processing Systems. (similar to LAM (linear action models), but different in interesting ways).

This paper actually applied low-rank approximation to our UOMs (universal option models) paper, and the motivation is similar. (they didn't cite our paper but instead motivated from Dayan's successor representation, which is also valid). 

The DRL literature seems to be very brave, seeking a universal representation to handle "all kinds of reward signals". Is that possible? I don't know but maybe some sort of approximation is possible. However, forcing a representation to handle all kinds of rewards will likely induce a representation that is overly over-parameterized (which seems not a problem for deep nets), which is needed to represent and approximate an infinite number of policies. I'm still comprehending this. 

- [A System to Predict Future Popularity: Learning to Classify](papers/trending.pdf). Lee, C., Yao, H., He, X., Su, C., and Chang, J-Y. WWW (poster), Seol,Korea, 2014. 

This is the paper out of our internship project. I kinda of miss my internship with Yahoo! Sunnyvale in 2013, when I learned Hadoop HDFs and MapReduce, processed lots of real data and worked with a group of friends Chi-Hoon, Martin, Sue, Xu, Kun, Haibo, and many others. Our project won a championship (CEO award) for "TrendingNow" (yahoo.com at the top right corner) that detects trending topics in Yahoo search engine. This paper learns to extract some growth pattern of query counts in search engines. One surprise we found at the time is that the query "Tom Clancy died" was already getting some hits in the query logs just a few minutes before his death was released by news. 
       
- [A Study of Temporal Citation Count Prediction using Reinforcement Learning](papers/citation.pdf). Yao, H., Sutton R. and Rafiei D. 2014.

- [Reinforcement Ranking](papers/rr.pdf). Yao, H. and Schuurmans, D. 2013. 

- [Approximate Policy Iteration with Linear Action Models](papers/lamapi.pdf). Yao, H. and Szepesvari, Cs. Twenty-Sixth Conference on Artificial Intelligence. AAAI. Toronto, Canada. 2012. 

- [MaxRank: Discovering and Leveraging the Most Valuable Links for Ranking](papers/maxrank.pdf). Yao, H. 2012.

- Linear least-squares Dyna-style planning. Yao, H. Technical Report TR11-04, Department of Computing Science, University of Alberta. 2011.

- Off-policy learning with linear action models: an efficient ["One-Collection-For-All-Solution"](papers/one_collection_for_all.pdf). Yao, H. In workshop on "Planning and Acting with Uncertain Models" at the 28th ICML, Bellevue, Washington, USA. 2011. 

- [Dyna(k): A multi-step Dyna planning](papers/dynak.pdf). Yao, H., Sutton, R. S., Bhatnagar, S., Diao, D., and Szepesvari, Cs. ICML workshop on Abstraction in Reinforcement Learning, Montreal, Canada. June 2009. 

- [Multi-step linear Dyna-style planning](papers/multi-step-dyna.pdf). Yao, H., Bhatnagar, S., and Diao, D. NIPS, Vancouver, BC, Canada. 2009.


- [LMS-2: towards an algorithm that is as cheap as LMS and almost as efficient as RLS](papers/lms2.pdf). Yao, H., Bhatnagar, S., and Szepesvari, Cs. The Forty-eighth IEEE Control and Decision Conference (CDC), Shanghai, China. December 2009. 


- [Temporal difference learning by direct preconditioning](papers/direct_preconditioning.pdf). Yao, H., Bhatnagar, S., and Szepesvari, Cs. Multidisciplinary Symposium on Reinforcement Learning (MSRL), Montreal, Canada. June 2009. I appreciate the citation from [this paper: Quasi Newton Temporal Difference Learning](http://proceedings.mlr.press/v39/givchi14.pdf) and the [TDprop paper](https://arxiv.org/pdf/2007.02786.pdf).


- [Preconditioned temporal difference learning](papers/ptd.pdf). Yao, H., and Liu, Z-Q. ICML, Helsinki, Finland. June 2008. I appreciate the four reviewers (who all acceptted in the first review round) and all the reviewers who had spent their time reading this paper and given valuable feedbacks. 
 
This paper was a very hard one for me. It is in fact my first paper at a renowned conference (The MR algorithm, which is related, was published at the ISAIM which is a workshop). It was sumitted four times since 2006. The first time it was submitted, one reviewer said "this paper contains brilliant ideas", which greatly encouraged me. The paper was submitted again to NIPS 2007. The paper received a score/confidence from three reviewers (both out of ten): 8/10, 7/10, 5/2, and an average score of 7.27. However, finally the paper was rejected. A reviewer said: "I was really hoping for a paper like this which applies well-known concepts from linear algebra to recent RL algorithms that end up solving linear systems. It is really interesting to see the connection between LSTD and LSPE, both of them being variants of a general preconditioning method". The third reviewer indeed said "However, if I am a minority and other reviewers find this paper clear and understandable, my review should be wholly ignored." A bit pity is that there was just no discussion and my paper got a rejection. [nips 2007 review](papers/ptd_nips.htm). For this reason, I (at least try my best to) take extreme care in reviewing papers especially those that I feel I don't understand well enough to judge sometimes.


For decades (1992-), off-policy learning with linear function approximation is problematic. Importance sampling gives an unbiased estimate of the target value function using the data collected from the behavior policy. However, importance sampling methods suffer from high variances due to that the importance sampling ratios are high. Is there another way of conducting off-policy learning? Gradient TD stands for a unique off-policy learning paradigm with linear function approximation, forming an important class of modern reinforcement learning algorithms. 


<div align="center">
<img align="center" src="papers/rates_gtd.png" style='height: 100%; object-fit: contain' class="inline"/>
</div>

This figure from the paper in fact shows that GTD is slow (in the steady-state sense). MR is the faster
version of iLSTD. iLSTD is the steady-state version of TD (TD cannot be faster than iLSTD). So the message is that we should improve GTD and TDC for the goals set in the Horde paper. 


- [Minimal residual approaches for policy evaluation in large sparse Markov chains](papers/mr.pdf). Yao, H., and Liu, Z-Q. The Tenth International Symposium on Artificial Intelligence and Mathematics (ISAIM), Fort Lauderdale, USA. January 2008. 

---
    
### Education: 
* Ph.D, University of Alberta, Computing Science, 2008--2014. 
* M.E, Tsinghua University, department of computer science and engineering, 2003--2006.
* B.S, Shandong University of Technology, department of mathematics, 1999--2003.  
* Zhaoyuan 1st Middle School, 1996--1999. 


### Thesis
- Model-based Reinforcement Learning with State and Action Abstractions. [Ph.D thesis](papers/yao_hengshuai_PhD.pdf), Hengshuai Yao, defended in 2015. 


### Volunteer service
* reviewing for AAAI, ICML, NIPS, UAI, AIStat, ADPRL(2014-2015), CIKM (2011-2013), WWW(2011-2013). ICML'22 Outstanding reviewer. 
* parent volunteering for Westbrook public school and Confed Hockey club. I like to watch these kids growing and interacting with their amazing smiles and passion of life. Recently I helped with the yearly Terry Fox run preparation. The roads on the windows were designed by me!

A fine Friday morning Alex doing a school patrol. Sis and Bro wanted to visit. They together with my wife taught me a lot things which I didn't imagine before having them.
<div align="center">
<img align="center" src="3hearts.jpeg" width="75%" height="75%" style='object-fit: contain' class="inline"/>
</div>


## Robocup Soccer 
I was a member of TsinghuAeolus (soccer simulation team at Tsinghua University) for World Cup Simulation League. 
Here shows a game of our team TsinghuAeolus playing against Everest in the final match at Robocup 2003. Our TsinghuAeolus was based on hierarchical reinforcement learning. Decisions the player has to make include: dribbling, passing, running, shooting, goal keeping, positioning (team position), resting, defending, etc. A high-level policy learns how to select a decision, and a low-level controller executes the selected decision. Both the high-level and low-level controller were learned using reinforcement learning.  
<div align="center">
<video src="videos/2d simulation game short.mp4" width="640" height="400" autoplay controls preload></video>
</div>

## Tetris
I developed a policy iteration algorithm to play a Tetris game. In this game, there are only hard shapes: "S" and "Z". The player was trained with data of randomly playing the game. 
<div align="center">  
<video src="videos/SZ tetris game short.mp4" width="640" height="400" autoplay controls preload></video>
</div>

---

### Students 
- [Shangtong Zhang](http://shangtongzhang.github.io/), Department of Computing Science, University of Alberta. mentored 2018 summer, now an assistant professor at University of Virginia. Shangtong taught me what is productivity, creativity and persistence. 
- [Mennatullah Siam](https://scholar.google.com/citations?user=AVPds3kAAAAJ&hl=ar), Department of Computing Science, University of Alberta. mentored 2019. Now a postdoc at York University. Menna taught me what is real passion for research. 
- [Khuram Javed](https://scholar.google.com/citations?user=wG1tGakAAAAJ&hl=en), Department of Computing Science, University of Alberta, mentored in summer 2019, and I was learning "meta" from him.  
- [Chao Gao](https://cgao3.github.io/), Department of Computing Science, University of Alberta, mentored in summer 2019 to 2020 on MCTS. Chao taught me how MCTS works (however it appears I didn't learn well at that time; Only in 2022 I had a chance to better grasp it) and the game of Hex, for which he won the world Hex Tournament Champion twice. 
- [Abhishek Naik](https://abhisheknaik96.github.io/), Department of Computing Science, University of Alberta, mentored in summer 2019. Abhishek taught me why the widely used discounted-reward objective, which is the standard RL setting, does not make so much sense, in particular, for episodes that are very long. 
- [Yangchen Pan](https://scholar.google.ca/citations?user=QyAsyYEAAAAJ&hl=en), Department of Computing Science, University of Alberta, mentored in summer 2019. Yangchen taught me the backward model for model-based RL. 
- Yi Liu. Department of Mathematical and Statistical Sciences, University of Alberta. mentored in summer 2019. We were working on UCB and I was learning the mathematics behind UCB from him. 
- Nazmus Sakib, cosupervised with Hong Zhang, Department of Computing Science, University of Alberta. Nazmus graduated in 2020. Nazmus taught me what is positively making things possible with magic fingers from hard work. 
- Arash Pourzarabi, a talented student I mentored in 2019 summer, always missed by us in [PS752](https://www.cbc.ca/news/canada/edmonton/alberta-victims-plane-crash-iran-1.5418751). Together we were working on feature decorrelation in the context of reinforcement learning. One month ago before that, he and me we were having lunch at Phobulous near UofA and I always remember his smile and bright eyes. I sent him flowers on the memorial day held by UofA for this flight that carried a few students and professors. We need to make peace for the world. I should cherish life and do good things, including research. I will only work on and publish good things that I feel (very) confident that it can advance the state of the art of our science. If still not serious enough, I will add that the advancement has to be fundamental.     

问渠哪得清如许？为有源头活水来。This old poem was written by an ancient scholar about doing research. The verbal meaning of this poem is that, I ask the waterway (a small river often built in front of farmlands for crop irrigation), "Why is your water so clean?" (It answers) "Because there is always water flowing in". If science and research are the ocean, students are the creeks and rivers. This waterway theory is my principle of doing research and working with students. The verbal meaning of the poem probably emphasizes readings. This is also true for research. **I should always help students achieve their goals, improve science, respect all my reading sources and genuinely give credits according to the truth** (regardless of my preference). Yes, I desire my personal success too. This is always the same as the goals above.    

**If I benefit from a reading, I cite.** **There are also circumstances that I didn't benefit from a reading, either because I discovered something independently, didn't read a paper that however indeed had a similar idea/algorithm/motivation, or this something is kind of well known (sometimes you're just not sure how well known is the thing). I still cite, for relevance.** Sometimes, after my paper is submitted, I did some additional double-check search and found similar ideas. This is not rare given the exponential growth of papers these days. For example, this happened for our "off-policiness" paper, which I found Marc Bellemare and Remi Munos already proposed the concept in 2016. Cite. Don't pretend to invent it, although sometimes you may discover it independently. For future readers, it is interesting for them to see the different perspectives where these concepts are proposed and used for. Ownership of ideas and methods is good for individuals but it's for future scientists to find how we improved science at our times. Another example: The "May Not Need Clipping" paper was mentioned by a reviewer when we submitted our off-policiness paper to AAAI 23. It's actually rewarding to think, "Great minds think alike", instead of "Oh, someone already discovered my ideas". 

<!-- 

## Openprice
The mobile App is the product of our startup Openprice which I cofounded in 2016. The app helps users manage their receipts and manage shopping.  

Uploading receipts and have it OCR-ed:
<video src="videos/upload receipt.mp4" width="640" height="400" autoplay controls preload></video>

Backend server extract structured data, send it back and display on user's phone:
<video src="videos/Receipt_details.mp4" width="640" height="400" autoplay controls preload></video>

Store search and catalog search (the girl on skype is Reka our App and UI designer)
<video src="videos/store search catalog search.mp4" width="640" height="400" autoplay controls preload></video>

Catalog we built (shown is Json format. The json files was injected to a MySQL database)
<video src="videos/catalogDemo2.mp4" width="640" height="400" autoplay controls preload></video>

-->


## Contact
my ccid "At@" ualberta.ca; the ccid is hengshu1


为人师者, 必先正其身。

德之未至，未敢为人师。

恒帅。


