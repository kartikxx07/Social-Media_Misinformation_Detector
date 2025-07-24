# Social-Media-Misinformation-Detector
In this repository, I have made an algorithm that checks whether the current content in a post is either factual or clickbait. I personally believe that misinformation is
a very big issue. With the help of this repository, I want to carry on this work of making this a better algorithm in order to detect misinformation. The key thing in this algorithm
is that I have classified misinformation into only two kinds: clickbait and factual errors. This is very vague, and with continued iterations of this algorithm in the future,
hopefully, I can make this more robust. Right now, I have used pre-trained models, and this code is not at all scalable for real-time or even batch processing and 
uses naive similarity matching in order to detect clickbait. In order to combat misinformation, we need a better metric than cosine similarity matching. The other thing that is
required is obviously data, a supervised dataset can be invaluable here, although I completely understand the limitations, even scraping of hundreds of millions of posts and self-labelling
is very challenging for a number of reasons, which does not include time to label. The other thing is extending the algorithm to also include filtering of accounts, RLHF, and also extending 
to video content, which will be the most challenging thing, and last but not least, for every commercial project, UX.
