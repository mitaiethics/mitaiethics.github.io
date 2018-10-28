---
layout: post
title: "Using AI to predict sexual orientation from faces"
image: "/assets/meeting1.jpg"
author: "Irene Chen"
---

It is undeniable that artificial intelligence (AI) has become increasingly more powerful and influential in our society. On the heels of [MIT's recent investment in a new school for computing](http://news.mit.edu/2018/mit-reshapes-itself-stephen-schwarzman-college-of-computing-1015), we created the AI Ethics Reading Group to build a university-wide community to discuss foundation and recent literature at the intersection of AI and society.

With over 150 participants on the newly formed email list, we held our first meeting on Wed Oct 24. While nothing can replicate the energetic interactions of an actual reading group meeting, we hope that we are able to capture some of the discussion points here. Also check out [our slides from the meeting](https://docs.google.com/presentation/d/1kQ02D0c2SNCOWj3nErSUnSrjkcjB2aWBE2Oh4f7WPZU/edit?usp=sharing).

{% include image.html url="/assets/meeting1.jpg" description="Eager minds in active discussion about the ethics of predicting sexual orientation from faces." %}

## Preliminaries
We had a healthy turnout of over 60 people on our first meeting -- not bad for sending out the first email a few days beforehand. After introductions and logistics for the reading group, we opened the floor with a few thought experiments. People were asked to align themselves across the room according to how they felt about each question and later briefly explain their thinking.
 1. Cash bail currently leaves innocent people in jail waiting for a trial because they’re too poor to pay bail. [California recently passed legislation around risk assessment tools](https://www.economist.com/united-states/2017/11/23/replacing-bail-with-an-algorithm
) that assign scores based on age, employment, drug use, and criminal history; however similar algorithms have been shown to produced biased recommendations. **Should states adopt legislation to reduce the cash bail system in favor of the risk assessment scores?**
 2. Companies are often overwhelmed by job applications, relying on humans (who may have their own biases) to read through and filter. [Recent attempts at a resume algorithm to screen applicants](https://qz.com/1427621/companies-are-on-the-hook-if-their-hiring-algorithms-are-biased/
) (e.g. at Amazon) were shown to be biased against terms involving women like “women’s chess champion” and biased for men named Jared who played high school lacrosse. **If you were CEO of a company, would you use algorithmic resume screening or stick with human resume screening?**

## Readings and Discussion
Our first set of readings covered the prediction task of predicting sexual orientation from faces. 
 * [Deep Neural Networks Are More Accurate Than Humans at Detecting Sexual Orientation From Facial Images](https://www.gsb.stanford.edu/faculty-research/publications/deep-neural-networks-are-more-accurate-humans-detecting-sexual)
 * [Do algorithms reveal sexual orientation or just expose our stereotypes?](https://medium.com/@blaisea/do-algorithms-reveal-sexual-orientation-or-just-expose-our-stereotypes-d998fafdf477)

The first reading described a deep learning experiment predicting the sexual orientation of dating app photos. Researchers used features extracted from a deep learning model and trained a logistic regression to achieve an area under the receiving operator curve (AUC) of 0.81 for men compared to an AUC of 0.71 for women. Using heat maps to uncover areas of highest signal, the authors then connected the results to prenatal hormone theory (PHT) which suggests that exposure to certain prenatal hormones can shape a person's sexual orientation and physiognomy. The model then identified so-called fixed characteristics (e.g. nose shape and jaw size) and transient facial characteristics (e.g. makeup, skin tone) most predictive of sexual orientation.

In response to the findings presented in first reading, the second reading delved into the experiment and highlighted other explanations for the findings. Using Amazon's Mechanical Turk crowdsourcing platform, the researchers found that many of the original findings may be related to preferences instead of physiognomy. For example, while gay men were more likely to wear glasses, the differences are not due to visual acuity but instead due to liking how they looked in glasses more. Similar results were found for facial hair preferences and enjoyment for the outdoors which causes darker skin. Lastly, the authors outlined a host of factors that may change the predicted sexual orientation for the same face including makeup, eyeshadow, facial hair, glasses, selfie angle, and sun exposure. 

With a large crowd of participants and many questions to debate, we split into smaller groups of 3-8 people with suggested discussion topics. After almost an hours of dialogue in the smaller groups, we reconvened in a larger group to share thoughts. Below are some of the opinions and concepts raised.
 1. It's hard to find a single positive use case for the first paper. The model is also limited by the use of dating profile pictures as training data, which makes generalization to other settings like Facebook photos challenging.
 2. One idea of how the authors of the first paper could have presented the ideas better is through separating ideas into a machine learning paper and a science paper in order to fully explore the implications and potential explanations for the findings.
 3. At best the algorithm to predict sexual orientation is finding spurious correlations in the data, which one participant described as evil. 

## Looking forward


In our first iteration of the reading group, we learned a few lessons to keep in mind for following meetings.
 1. **Keep discussions specific.** Discussing the pros and cons of cash bail and risk assessment scores is more interesting when discussing one state's pros and cons when considering which law to pass. Debating whether or not to use biased algorithms feels more nebulous and can end with grand statements with fewer opportunities for others to engage.
 2. **Establish norms for debate.** Inevitably discussions can get heated, especially while discussing charged topics. It's important to set ground rules early to maintain an inclusive, respectful, and considerate environment. 
 3. **Beginners and experts welcome.** At first, I was apprehensive that the three organizers were computer science PhD students without any ethics backgrounds. Luckily, the MIT community has a large crowd of perspectives to lend, and both beginners and experts had plenty to share.

We also polled informally for future topics to wrestle together.
 1. **Autonomous weapons**: As AI and warfare progress together, soon we will be able to deploy lethal autonomous weapons systems. Should these be banned and on what basis? If banned, how do we prevent underground research from creating them anyway?
 2. **Privacy**: With ubiquitous AI systems, where is the line for individual privacy? How can someone opt-out of AI? What level of surveillance should be acceptable? 
 3. **Ranking of forum posts**: Currently in online discussion platforms, majority rule for forum post rankings creates a winner-take-all system. How can we showcase a diversity of perspectives in ranking algorithms?
 4. **Synthetic data**: The ability to create fake images, videos, and news stories could have wide reaching implications for the future of truth. How can we detect, regulate, and protect against this troubling line of research?
 5. **AI human rights**: When algorithms become incredibly advanced so much so that they are almost human-like, how should we think about humane treatment? What is suffering for an algorithm?
 6. **AI and jobs**: As more jobs become replaced by algorithms -- particularly repetitive or other easily automated professions -- how can we create room for people to retrain and assume new careers? 
 7. **Inequality and AI**: Access to AI has widened an existing wealth gap as companies can now reap benefits without employing nearly as many workers. Relatedly, the computing resources to be able to run deep learning models can be a barrier to entry for some communities, countries, and continents. How should we distribute wealth created by machines?

Overall, we were thrilled with the turnout for the first meeting, and hope everyone joins us for the next meeting on Wednesday November 7.
