# Navigating Reddit's Political Terrain Through LDA-Powered Topic Modelling

## Abstract
Our project, building upon the foundation laid by the [referenced research paper](https://www.nature.com/articles/s41586-021-04167-x), endeavors to uncover the intricacies of online polarization within the most polarized subreddits. By applying Latent Dirichlet Allocation (LDA) to comments from politically divided communities, we aim to dissect the main topics discussed, discerning whether they align with the subreddit's purpose or stem from political perspectives. The project's motivation lies in comprehending the origins of polarization identified in the paper, shedding light on the thematic underpinnings of divisive online discourse. Through data cleaning, anonymization, and LDA modeling, we seek to draw meaningful insights. The main visualization, a 2D plane depicting the topic spread via multidimensional scaling, will offer a visual narrative of the prevalent themes, enabling conclusions about the relationship between discussed topics, subreddit descriptions, and political views.

## Research Questions
Primary: *What are the predominant topics discussed in the comments of the most polarized subreddits, and to what extent do these align with the subreddit's title/description versus reflecting political views?*
> Additional Questions
> - How does the identified topic distribution vary between the most polarized subreddits on the left and right sides of the political spectrum?
> - Are the topics driving polarization on Reddit temporally aligned with external events, and if so, how does this temporal alignment manifest in the comments of the most polarized subreddits?





## Datasets
We will use the Text Dataset which includes both the metadata and text for both comments and submissions on Reddit from Jan 2019 - June 2021.

## Methods
### Analysis Strategy
To address the primary research question – understanding the predominant topics discussed in the comments of the most polarized subreddits and the extent of alignment with subreddit titles versus reflecting political views – our analysis strategy integrates various approaches. We plan to employ Latent Dirichlet Allocation (LDA) for topic modeling to extract latent themes from comments. Additionally, we'll conduct text and sentiment analysis to grasp the overall tone, employing keyword frequency analysis to identify terms associated with political views or alignment with subreddit topics. Visualization techniques like multidimensional scaling, word clouds, and bar charts will be utilized to present findings in an accessible manner. Comparative analyses will assess topic distributions among left-wing and right-wing polarized subreddits.

### Managing Dataset Size
To handle dataset size, we'll consider subsampling to focus on a representative subset while maintaining diversity. Data reduction techniques may be applied based on factors like computational power/time.

### Data Cleaning and Transformation
Cleaning procedures involve removing duplicates, irrelevant data, and anonymizing user information to uphold privacy. Text data preprocessing will include tokenization, stemming, and the removal of stop words to prepare it for LDA modeling. Enrichment will involve incorporating subreddit metadata, such as titles and descriptions, to facilitate alignment analysis.

## Organization within the team
Considering both my teammate and I have similar schedules, we will be pair programming the entire project. Instead of dividing the work evenly, we prefer working together on every aspect as we can share ideas.
