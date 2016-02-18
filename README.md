# PubmedCrawler
A crawler to collect Pubmed abstracts.

The primary goal of this project is to create a classifier that can automatically classify articles into different clinical categories according to topics and clinical evidence level. Normally clinicians search and browse pubmed to acquir newest updates for articles in related fields. However, not every article in the repository is equally significant in terms of clinical pratice. Biological studies are aimed to reveal the underlying mechanism of disorders and corresponding treatments but provides little information about whether the treatment is effective in a certern population. Even Epidemiological studies that directly collect data from human weighted differently in clinical perspective. A well designed randomized trial in erlder patients is thought to be more accurate that observational studies, while it does not tell us much about the effectiveness of treatment in the younger population. To avoid the trivial work to read through all of the articles to figure out their grade of evidence, researches write systematic review and meta-analysis periodically to summarize the evidence architecture of a clinical topic. Medical associations gather conferences and publish clinical guidelines to absorb newest evidences into clinical practice.

There is a huge gap between publishing a finding and benefiting the patients. It will take an even longer time to incorporate evidence in the fields which has insufficient active researchers to update the systematic review and meta-analysis. Therefore, with the help of Natural Language Processing, this project is aimed to automate the process of evidence extraction from published articles. I hope this program will help clinicians focus on the clinical evidence itself rather than waste time on searching and evaluating papers.

Tasks \n
1. Crawling pubmed abstracts according to a certain of search terms.
2. Recognizing and tagging the abstract to obtain information on the PICO (Patient, intervention, Control, outcome) and study design.
3. Classifying crawled entries into relevant/irrelevant articles according to PICO principle.
4. Retrieving full text of crawled articles and extract sufficient information with regard to evidence strength. (Sample size, source population, Bias control, inclusion and exclusion criteria and effect size).
