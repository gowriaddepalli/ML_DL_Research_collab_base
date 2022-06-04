How to do literature review when getting into a new field.
Wenzhe Shi
Wenzhe Shi
(He/Him) • Following
Follow for Recommender Systems, Applied Research topics
2d • Edited • 2 days ago
Applied Research, how to do literature review when getting into a new field:

In our previous post about applied research we suggested that whenever you dive into a new problem space you should start with a literature review to understand the state-of-the-art. 

Different people have different ways of doing this, and here is a step by step guide of what I usually do. Let’s be honest, I have been doing this since my PhD (~2010) so both the tools and methods I use might seem outdated, antiquity even. So please share what works for you as well.

First, think of a few keywords and start with a Google scholar (https://lnkd.in/g33M8bJe) search. Then sort the papers by citation, and take the most cited papers (3-5) in recent five as well as ten years. This leads to up to 10 papers in total.

Then let's find papers that are cited by and cited these papers, we can do this by clicking the cited by in Google scholar, find the most cited papers in those papers. I recommend getting all papers that have more than N = 100-1000 citations. N depends on the size of the field. For recsys I will go with 100, for CV I will go with 1000. Half way through this, we would get a more accurate sense of what are the keywords of these papers and update the keywords.

These papers, once we finish reading them, should give us a good overview of the field. However, we want to add recent top conference papers to have a view of what are the key challenges / trends people are working on today. We should already know that from reading the papers we collected so far. I will read all related papers from those conferences in the past 5 years. If I have limited time, I read the orals only.

The above steps should give us good coverage for industry solutions already, since Google, META and other top companies publish regularly. However if needed, we should get a list of reputable company names, companies we know are SOTA in the problem space and read their blog posts in addition to papers.

Now we should have a good understanding of the development of the field and what are the key technical challenges remaining, ON PAPER. However, our literature review is not complete until after we implement and/or reproduce the baseline methods ourselves, both on public dataset as well as on the specific production dataset we are working with. Then we will see first hand, what works and doesn’t work. This is the key stage of determining what is SOTA: whatever works best on our dataset and problem out of all the methods we collected so far from the literature review is the SOTA method for our dataset and problem. And after that we can finally start the iterative process to explore the problem space.

One last thing to remember, when we are reproducing the results, we should make sure the method we are testing is not under-performing due to bugs. And make sure the models are well tuned, aka, we explore all sensible hyper parameters, for our problem.


Reference: https://www.linkedin.com/posts/dksahuji_google-scholar-activity-6938100704200769536-wqOF/?utm_source=linkedin_share&utm_medium=android_app
