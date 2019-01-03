---
layout: post
title: "How AI can undermine online privacy and anonymity"
author: "Jack Cook"
---

It only took a couple of years for Bitcoin to draw national attention in the media. As the value of the digital currency began to skyrocket, there was one question on everyone’s minds: who is Satoshi Nakamoto? The creator of Bitcoin, Nakamoto is the owner of nearly 1 million bitcoins. At Bitcoin’s peak value, this stash would have been worth $19.4 billion, [making him or her one of the world’s 50 wealthiest people](https://qz.com/1159188/bitcoin-price-approaches-20000-making-satoshi-nakamoto-worth-19-4-billion/). While many have tried to figure out Nakamoto’s identity using clues ranging from timezones to writing styles, computer science researchers have pointed towards the ability of artificial intelligence to identify anonymous programmers.

By training a classifier on a few samples of code from participants in Google Code Jam and open-source authors on GitHub, researchers have shown that it’s possible to identify the author of a file of code with reasonable accuracy, which raises a couple of ethical issues. While artificial intelligence may never perfectly solve this problem, imagine a program existed that could identify the author of any code sample with perfect accuracy. When would it be okay to use that program? What if it could identify the creator of a global malware attack? What if it could identify the creator of a tool used to circumvent censorship? We debated these questions, among others, in the MIT AI Ethics Reading Group, where we had a broader discussion about the potential implications of AI for online privacy and anonymity.

## Beginning Exercise

We started the meeting by discussing the potential effects of products that are designed for children. Many experts have criticized products such as “YouTube Kids,” “Echo Dot Kids Edition,” “Messenger Kids,” and others out of concern for children's privacy and possible developmental issues. I posed one question to the group: who is responsible for making sure these products don’t have a lasting impact on children?

We debated between holding parents, companies, or the government accountable, but there didn’t seem to be a clear winner. For example, if all parents are expected to keep their kids away from something, is it ethical for companies to create it? I pointed out a recent New York Times article that highlighted how parents in Silicon Valley have overwhelmingly opted for less “screen time” for their kids, illustrating an education divide; many parents are unaware of the potential ill effects of technology on their children.

Similarly, many schools (in the U.S. and in other countries) have organized [field trips to Apple stores](https://www.apple.com/retail/fieldtrip/) (which on its own was surprising to many of us). In France, [these were recently banned](https://news.cgtn.com/news/3d3d514f3251444e77457a6333566d54/share_p.html) after a court ruled that marketing to young children was unethical. However, we saw this as one clear case where a country’s government was able to protect young children effectively.

## Reading and Discussion

For this week’s meeting, we read from the following sources to gain background on how AI can undermine online privacy:

- [Even Anonymous Coders Leave Fingerprints](https://www.wired.com/story/machine-learning-identify-anonymous-code/), which references the following paper:
  - [When Coding Style Survives Compilation: De-anonymizing Programmers from Executable Binaries](https://arxiv.org/pdf/1512.08546.pdf)
- [Facebook/Cambridge Analytica: Privacy lessons and a way forward](https://internetpolicy.mit.edu/blog-2018-fb-cambridgeanalytica/)

The first reading discussed a study in which researchers were able to use AI to predict the authors of code samples by constructing abstract syntax trees that exposed each programmer’s style. They achieved 92% accuracy on a sample of 191 programmers, and 83% accuracy when they expanded the sample to 600 programmers. The researchers also found that their results were more accurate on experienced programmers, which may be due to novice programmers’ tendencies to copy and paste samples of code from the Internet. The second reading described the Cambridge Analytica incident, which was brought to light earlier this year by The Guardian and The New York Times.

We then split into smaller groups to discuss a variety of discussion questions relating to the issues presented in these readings, and reconvened about an hour later to discuss our findings as a group. Here were a few of our key takeaways:

1. Companies should not self-regulate, and we pointed out that privacy has essentially been a clear market failure. Companies have little incentive to respect their users’ privacy, especially when selling user data helps them stay profitable.
2. A federal agency may serve consumers’ best interests with respect to protecting our collective right to privacy. Similarly to how the FDA protects consumers by requiring animal tests, an administration focused on ethics could set clear boundaries for tech companies. However, due to the history of consumer of protection in the U.S., this is unlikely to happen anytime soon.
3. Some amount of tracking is required for companies to remain profitable, and asking users to pay for software that was previously free is out of the question. Grocery store rewards cards are an example where people will give up privacy in exchange for small discounts.
    - Food for thought: DuckDuckGo is able to make a profit, even though they don’t sell individual user data. Unclear if their model could work well for other companies, but may be worth investigating.
4. There’s a fine line between making inferences about someone and intruding on their life, and it’s difficult to say where that line falls. It’s also difficult to say how to resolve issues caused when someone loses their privacy as a result of someone else’s actions. For example, when [someone gives their contacts’ information to Facebook](https://bits.blogs.nytimes.com/2012/02/15/google-and-mobile-apps-take-data-books-without-permission/), or when [a relative gives their DNA to 23andMe](https://www.nytimes.com/2018/04/27/health/dna-privacy-golden-state-killer-genealogy.html).
5. When companies make difficult decisions, transparency and appeals to ethics are very much appreciated (as opposed to “PR speak”). For example, when Cloudflare took the Daily Stormer offline, Matthew Prince, Cloudflare’s CEO, [wrote a detailed blogpost](https://blog.cloudflare.com/why-we-terminated-daily-stormer/) explaining what the company did and why they did it, which helped others understand Cloudflare’s careful decision-making process.
