## Diminishing Privacy And Centralization Of Power: The Problem
(Project State: This document is under development, please revisit it at a later time, a lot more content is yet to be added/refined)

There is a set of fundamental problems we face due to the current business model of heavily used internet services.
This document aims to inform about the extent of tracking/servailnace in the modern world and how our privacy and attention is the currency we use to pay for these "free" internet services (and even paid ones). How the loss of privacy has far deeper implications than one may initially believe. How business model is leading towards a potential future where the tech giants could have unprecedented power.
This project is a collection of arguments and thoughts (backup up by evidence) on why your privacy matters, even if you believe you have nothing to hide from anyone. A resource you can point your friends and family to, when explaining why they should care about privacy and what they can do about it. Check our the sister project "Privacy Fighter" to find out what you can do right now as a first step to towards protecting your privacy.


## Table of Contents
1. [Privacy: The Currency Of Modern Internet](#currency)
2. [The Illusion Of "Free" Internet Services](#illusionoffree)
3. [The illusion of "Anonymous" data collection](#illusionofanonymous)
4. [Algorithms: Shaping Minds and Societies](#algorithmsshapingminds)
5. [The Future Of Increased Computing Power And AIs](#futureofais)
6. [The Dangers Of Social Norms](#socialnorms)
7. [The Black Boxes We Are Supposed To Trust:](#futureofais)
8. [Incompetent Legal Systems](#futureofais)
9. [Social Media and Spread of Misinformation](#socialmedia)


#### 1.0 Privacy: The Currency Of Modern Internet <a name="currency"></a>

Tracking is built deep within the infrastructure of most services on the web. We are all aware that companies like Google, Facebook generate their revenue by tracking and understanding our behaviours and serving ads that we are likely to click on based on our preferences/behaviours. I believe most of us are unaware of the extent of this tracking, the fact that companies like these track all activities even when we are not logged in or using their service at all.
**For example Google tracks your activities across >70% of all websites, even when you are not logged into Google or using any of it's services (search engine, Chrome).**
Here is the breakdown of tracking networks of the major companies that have their trackers in internet facing websites.


<p align="center">
  <img src="https://gitlab.com/JGill/privacy/raw/master/data/tracking%20in%20top%20million%20websites.png">
</p>


Fig. 1 From one of the largest and most detailed study on online tracking conducted.[1] The figure shows organizations with the highest third-party presence on the top 1 million sites (Alexa rank). **Google/Facebook/Amazon and many others track you across all websites not just their own**


![prompt](https://gitlab.com/JGill/privacy/raw/master/data/third%20party%20trackers%20in%20categories.png)


Fig. 2 The prevalence of third-parties by Alexa site category, split between tracking and non-tracking third parties [2]. Shows most third parties linked in webpages are actually trackers. When you browse a news site, on average there are ~38 third parties tracking your news consumption.

![prompt](https://gitlab.com/JGill/privacy/raw/master/data/washingtontimes-trackers-blocked.jpg )


Fig. 3 A screenshot I took of uBlock Origin (extension), detecting and blocking 42 connections to trackers and ad servers on a News site washingtontimes.com.

**“They who can give up essential liberty to obtain a little temporary safety deserve neither liberty nor safety.”
― Benjamin Franklin**

**Yet we have been eased into giving up privacy not even in exchange for security but for conveniences.**
**We all use seemingly "free" online services and accept their legally binding "terms and conditions" without giving them any thought.**

It's not just you, as illustrated in [this](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2757465) study pretty much no one reads "Terms and conditions" or "Privacy Policies" of online services [3]. This is because they are deliberately made lengthy and hard to read. Sometimes even using techniques like small fonts and capital letters [4].


How is it that companies that provide online services such as Google and Facebook are amongst the biggest and fastest growing enterprises? This is because they have figured out ways to monetise user generated information.
There are large number of data brokers who's sole business is to profile/categorise people. whose names you'd have not heard the of. (Rubicon Project, AdSonar, Quantcast, Pulse 260, Undertone, Traffic Marketplace.) [103, BS] [citation lost: reee]
Even if you fully trust all of these organisations with your private data, it is vital to understand this trade and it's implications.
Everyone seems to relate that individuals in these corporations having access to our personal data is creepy. The bigger problem is not that individuals in these corporations can access and even exploit personal data about you (even though that's a concern and it does happen [5]).
The main problems regarding the loss of online privacy are for more fundamental. [ELABORATE]

Have you ever had the experience, when you thought about a product or needed one and ads about it magically showed up. Some may assert their digital devices must be listening to their conversations. The matter of fact is, that's not even needed. The through tracking of your online activities can reveal who you are as a person, what you do, what your likes/dislikes are.
Google CEO: "We Know Where You Are. We Know Where You've Been. We Can More Or Less Know What You're Thinking About."
Eric Schmidt in 2010 [6].
That was said in 2010. The online tracking has become far more invasive since then and business executives are far more careful to not make public statements like this.

So what does you data and metadata say about you? Take your Facebook likes example, just by analysing your Facebook likes, your race, political preference, sexual orientation can be predicted with high accuracy [7].
But that's just likes, Facebook tracks much more including your browsing behaviour across more than 8 million websites. That is, even when you are not using Facebook, Facebook tracks you on every website that have their "Like" or "Share" buttons on it.[8]
Facebook knows about; Where you go, Your financial status, Status updates you almost post, Apps you install, Apps your friends install, even when you're feeling low. - Bruce Schneier [9]
There are cases, when Facebook was shown to know something deeply fundamental about their users, even before they realised it themselvesas; their own sexual orientation [10].


#### 2.0 The Illusion Of "Free" Internet Services <a name="illusionoffree"></a>
Significant portion of the software/technologies that have enabled us to create the internet, the World Wide Web and the infrastructure of dot-com companies are open source and "free" as in freedom and "free" of cost.
These hundreds of thousands of people who have created these technologies and allowed others to freely use, modify, built upon and redistribute all that for the advancement of society and free of charge are the true heroes of this technological revolution.
Most of the "free of charge online services" on the other hand, that have operational costs and are run by companies are not really "free".
**These "free" services provided by profit making organizations are given to you in exchange of the ability to surveil and make use of your private information. Currently for the most part to serve personalised ads.**

**These "free of charge" services are not the product, we are not the customers, our attention and privacy is the product, advertisers and third parties interested in our data are the customers.**
This thorough surveillance is certainly not limited to "free" services. Companies that sell products/services directly to us like Amazon or Uber also heavily utilise their user's data/metadata.

#### 3.0 The illusion of "Anonymous" data collection: <a name="illusionofanonymous"></a>
Many companies claim to not include any personally identifying information in their data collection and assure us that our identity is protected. This can be deceptive. It is well understood and research demonstrates that it is very easy to de anonymise data by correlating different data sets. As demonstrated in the cases of AOL search data of 657,000 users, Netflix's 10 million movie rankings by 500,000 anonymized customers. [11]
Even if two or more data-sets do not have "personally identifying information" on their own, their correlation can reveal this information.
"This is why regulation based on the concept of “personally identifying information” doesn’t work." Bruce Schneier [11] [Data And Goliath - Bruce Schneier. P. 93].


#### 4.0 Algorithms: Shaping Minds and Societies:<a name="algorithmsshapingminds"></a>
For the most part, the state of the world is what Google search results report to you, what comes up in your Facebook feed, your news feeds. And results are different for everyone. Decided by the machine learning algorithms. This is because our "feeds" are personalised, Google search for example displays the result to you that it's algorithms think you are more likely to click on/ interested in. This phenomenon is called the "Filter Bubble" [12] [13]. It can lead to many social problems such as increase in political / cultural / racial divides.
For example when a platform like search engine or social media feed gets a good idea of what your political preference is, it would show you more results/articles that subscribe to your political view, as you are more likely to click on them and spend more screen time on them.
These filter bubbles keep reinforcing the believes we currently hold (or are exposed to for the first time) and keep feeding back confirmation bias to us. This goes against the core idea of rationality; being self critical. This effect can be seen in the emergence of movements like anti-vax, flat earth, climate change denial.

**The algorithms answer our queries, show us news articles, decide articles from what political view should be shown to us, really dictate how we view the state of the world. These algorithm are designed to do one thing, generate maximum traffic and screen time, not to create healthy, rational societies.**

I do not believe that anyone at companies like Youtube (Google) intentionally feed the constant flow of controversial content to susceptible users. This is an example of human psycology hacks that machine learning algorithms (designed with the goal to maximise screen time) are ought to find and exploit. Nothing is done about it because the business model benefits from it.





#### References:<a name="references"></a>

[1][S. Englehardt and A. Narayanan, “Online Tracking: A 1-million-site Measurement and Analysis,” in Proceedings of the 2016 ACM SIGSAC Conference on Computer and Communications Security - CCS’16, Vienna, Austria, 2016, pp. 8.](http://dl.acm.org/citation.cfm?doid=2976749.2978313)
[2][S. Englehardt and A. Narayanan, “Online Tracking: A 1-million-site Measurement and Analysis,” in Proceedings of the 2016 ACM SIGSAC Conference on Computer and Communications Security - CCS’16, Vienna, Austria, 2016, pp. 10.](http://dl.acm.org/citation.cfm?doid=2976749.2978313)
[3][J. A. Obar and A. Oeldorf-Hirsch, “The Biggest Lie on the Internet: Ignoring the Privacy Policies and Terms of Service Policies of Social Networking Services,” Social Science Research Network, Rochester, NY, SSRN Scholarly Paper ID 2757465, Jun. 2018.](https://papers.ssrn.com/abstract=2757465)
[4][Terms and Conditions May Apply.](https://www.imdb.com/title/tt2084953/)
[5][“Uber said it protects you from spying. Security sources say otherwise,” Reveal, 12-Dec-2016.](https://www.revealnews.org/article/uber-said-it-protects-you-from-spying-security-sources-say-otherwise/)
[6]N. Saint, “Google CEO: ‘We Know Where You Are. We Know Where You’ve Been. We Can More Or Less Know What You’re Thinking About.,’” Business Insider Australia, 05-Oct-2010. [Online]. Available: https://www.businessinsider.com.au/eric-schmidt-we-know-where-you-are-we-know-where-youve-been-we-can-more-or-less-know-what-youre-thinking-about-2010-10. [Accessed: 06-Apr-2019].
[7][A. the A. / S. D. S. A. D. was a senior privacy analyst at A. from 2010 to 2013 S. now an early stage investor at Accomplice,  a V. firm in Cambridge, and MA., “Facebook Likes predict sexual orientation, religion, and more,” Online Privacy | Abine, 12-Mar-2013. .](https://www.abine.com/blog/2013/facebook-likes-predict-who-you-are/)
[8]P. Martineau, “Facebook is tracking you on over 8.4 million websites,” The Outline. [Online]. Available: https://theoutline.com/post/4578/facebook-is-tracking-you-on-over-8-million-websites. [Accessed: 11-Mar-2019].
[9]“You Probably Don’t Know All The Ways Facebook Tracks You,” Gizmodo Australia, 13-Jun-2017. [Online]. Available: https://www.gizmodo.com.au/2017/06/you-probably-dont-know-all-the-ways-facebook-tracks-you/. [Accessed: 11-Mar-2019].
[10][“Facebook knows you’re gay before you do,” AMERICAblog News, 20-Mar-2013. .](http://gay.americablog.com/2013/03/facebook-might-know-youre-gay-before-you-do.html)
[11][B. Schneier, Data and Goliath: The Hidden Battles to Collect Your Data and Control Your World, 1 edition. New York London: W. W. Norton & Company, 2016.](https://www.amazon.com/Data-Goliath-Battles-Collect-Control/dp/039335217X)
[12][E. Pariser, Beware online “filter bubbles.” .](https://www.ted.com/talks/eli_pariser_beware_online_filter_bubbles)
[13][E. Pariser, The Filter Bubble: What the Internet Is Hiding from You. New York: Penguin Press, 2011.](https://www.amazon.com/The-Filter-Bubble-Internet-Hiding/dp/1594203008/)
