# Tiers-Lieux: comparing the way places define themselves and how they are talked about on Twitter (working paper)

## Background and context

“Transitional urbanism” is a term used to describe a range of practices and projects that have emerged over the past ten years in the field of urban development. These projects typically involve the temporary (1-3 year) occupancy of urban brownfield sites by a mix of local SMEs, artists and community organisations while the sites await approval for redevelopment or demolition. The buildings can be publicly or privately owned; examples include industrial sites, warehouses, transportation infrastructure, office space and municipal buildings. 

Unlike squats, with which they share some features, transitional urbanism projects are regulated (tenants sign leases and pay nominal rent to the building owners) and are increasingly being encouraged by municipalities, who see them as a way to expand community involvement, preserve low-cost space for non-profit and cultural activities and foster local economic development. In fact, some local authorities now use the permitting process to encourage site owners to initiate transitional urbanism projects and then incorporate aspects of them into their final building plans, resulting in permanent space for local and community-based activities. 

In France, transitional urbanism projects are often referred to as “tiers-lieux”: literally “third places”, or hybrid places – defined to an extent by their “in betweenness”, between temporary and permanent, public and private, single and multiple uses, ownership and occupancy, top-down and bottom-up. 

The concept of third places was initially described and popularised by the American sociologist Ray Oldenburg in his influential 1989 study The Great Good Place. Oldenburg coined the term to refer to places of public sociability - pubs, cafés, barber shops, community centres, etc. – in contrast to first places (the home) and second places (the workplace). His study foregrounds their role in forming and maintaining community ties, even going so far to refer to them as the grassroots of democracy and linking them to older examples of public fora like the French café during the Revolutionary period or the London coffee house. 

In the contemporary French context, this collective, community-building aspect has merged with notions of temporary occupancy and adaptive reuse. The association France Tiers-Lieux provides the following definition of a tiers-lieu from the perspective of transitional urbanism, highlighting the role of collaboration and their sui generis nature: 

“A third place is a collective approach in service of the public good, part of a process of local cooperation starting from its conception. By their very nature, they are unique and cannot be replicated. They emerge from a group of stakeholders who together wish to create new economic or social dynamics in response to the challenges of their local area. It is by bringing inhabitants and future users of a place together, shaping the contours of its active community in doing so, that the activities in the place are defined and the project is adapted.”

As of 2021, there were over 1800 tiers-lieux in France. There is now significant political and research interest in these places thanks to their potential to inject new energy, investment and community engagement into local economic development, not least because many of the sites in question are in economically depressed or post-industrial areas. 

A range of institutional, non-profit and private stakeholders has emerged to work on identifying, promoting, funding and gathering best practices on the development of tiers-lieux. France Tiers-Lieux is a public association created with the support of the French Ministry of Territorial Cohesion to monitor and generate policies about tiers-lieux. Other stakeholders include operational urban planning collectives and consultancies (Plateau Urbain, Sinny & Ooko, Approche.s), urban planning institutes (Institut Paris Region, ANRU), and trans-disciplinary researchers in city planning, cultural projects and the social economy like Raphael Besson, Cécile Diguet, Arnaud Idelon and others. There are experimental university degrees offered in managing tiers-lieux and continuing education courses to help practitioners apply for public funding. Emblematic sites have emerged and received major media coverage and popular support (ex. Les Grands Voisins in Paris, Coco Velten in Marseille).

Despite this proliferation of attention and stakeholders, an open question remains squarely at the centre of this work: what exactly is a tiers-lieu? 



## Motivation of the research question

“I know it when I see it” – threshold test established by Justice Potter Stewart in the 1964 US Supreme Court decision on obscenity and the definition of hardcore pornography

Elephant test: between “what they say they are” and “what people say they are”

Bridging the gap between what they do, what they are and what they say they are is important because it will help establish a baseline for measuring their impact, the holy grail of urban development projects, one that remains frustratingly elusive because of the lack of consistency and comparability between indicators. 

Taking the definition by France Tiers-Lieux at face value, how can standards, regulations and policies be made to help promote tiers-lieux if they are “unique and cannot be replicated”? This claim may closer to a provocation or a philosophy than to a legal or standard-setting definition – not least because France Tiers Lieux has also created a list of characteristics shared by tiers-lieux, meaning that they are not entirely resistant to categorization and norms. And other institutions, notably APUR (Paris Urbanism Agency), have studied the legal framework for tiers-lieux in order to build a more solid foundation for such projects within existing planning law and regulations. 

But the dilemma remains that, because of their hyperlocal, collaborative nature and bottom-up (rather than top down) approach to developing and running them, there is a philosophical resistance to standardisation amongst practitioners and stakeholders in tiers-lieux.

In order to develop policies to support, subsidise and quantify their impact, there needs to be some way to objectively characterise what a “tiers-lieu” is, rather than only what it does. In practical terms, such a characterisation would allow tiers-lieux to be written into local planning documents, to make the legal framework around them more robust, and create a baseline for measuring their impact on issues like community participation, real estate values and local economic development. 

This issue has been examined by several practitioners, some directly has been examined by researchers and practitioners from several angles.

Researchers in urban planning have used text mining, topic modelling and other NLP techniques to examine trends and patterns in urban planning documentation. The difficulty of working on the topic of tiers-lieux is that they are not currently written into planning documents, being relatively new and faced with the present challenge of definitions. 

Etienne, et al. (2019) have used text-mining to investigate urban planning documents in the French department of La Réunion for identifying differences in local planning strategies. Using the entire body of local planning documents (PADD) on the island  as a corpus, their correlation map, clustering and topic modelling exercise identified significant similarities between the documents, which they needed to analyse to determine whether they were attributable to the writer of the documents or to the hierarchical approach of urban planning in France and in Reunion Island. They also analysed whether differences between the documents were a response to local characteristics. Methodologically, they noted that high predominance of common vocabulary limited the comparative power of the exercise, with frequent recurrence of common urban planning terms like “renewal”, “diversification” and others.

Another relevant paper by Yuan Lai and Constantine Kontokosta (2019) uses modelling to investigate the thematic structure and spatial-temporal patterns of building renovation and adaptive reuse in a number of American cities. They use NLP and topic modelling to examine the “thematic structure of construction activities from permit descriptions and merge with other urban data to explore the dynamics of urban change”. Proceeding through text mining to “identify popular words, popularity change and their co-appearance likelihood”, they conduct topic modelling using LDA and integrate the model with geo-spatial data on buildings to “identify spatial, temporal, and thematic patterns of urban redevelopment and regeneration”. We will broadly adapt this approach to our study, with significant differences in the source material for the corpus. 

Unlike the aforementioned examples, however, there is not a large, standardized corpus of urban planning documentation for us to use for text mining treatments. 

We propose to reconcile these diverse threads by examining two “bottom-up” or “crowdsourced” sources to data to constitute a corpus and a treatment. If tiers-lieux are going to be defined, in a sense, as “they are what we say they are”, then we can at least measure this against what users (or people on the internet) say they are. This is both an interesting way of approaching the question of, and aligns with the crowdsourced, collaborative and open-ended philosophy of these places. 

Can we reconcile this dilemma by using “crowdsourced” information from Twitter?  We will use data from Twitter (specifically the 16,000 most recent tweets with the hashtags #tierslieu and #tierslieux) to form a corpus, a sort of crowdsourced definition. Recognising that Twitter users do not necessarily set out to define or characterise these spaces, we can nonetheless gather useful information about “what people/users are saying” as opposed to “what the people in charge of tiers-lieux are saying” from this corpus. 

On the other hand, to understand how these sites define themselves, we will extract data from the website of Commune Mesure. Calling itself a “data panorama”, the site is a non-profit initiative created to serve as  a census of tiers-lieux in France. It has notably given participating sites the opportunity to write about themselves in freeform and also to use a number of predefined characteristics that fit their mission statements. 

Our approach is progressive and exploratory, looking at the data from three different lenses: 

- Change of key Twitter terms associated with #tierslieux over time 
- Values from the CM site mapped onto the total top words from the Twitter corpus
- Spatially mapping the Commune Mesure

Mapping each of the 72 sites onto the topic model to see what characteristics emerge. Can we classify or organise the sites based on their affinities with the model derived from keywords associated with the hashtags #tierslieux and #tierslieu?

## Data and Methods

We used two datasets to conduct our experiment: 

1. **Commune Mesure**, a publicly funded website that gives tiers-lieux space to define themselves and co-develop metrics for measuring their impact. We scraped the website (https://communemesure.fr/app/les-lieux) using the BeautifulSoup and urllib packages of python. We then collected the data about the name of the site, its address, its geographical coordinates, founding values, and values used to self-describe 38 different “tiers-lieux” sites.

2. **Twitter**. There are slightly more than 24,000 tweets in existence with the hashtags #tierslieux and #tierslieu. We used the twitter API and the MINET library to scrape tweets with hashtags #tierslieux and #tierslieu. There were ~19k tweets associated with #tierslieux and ~6k tweets associated with #tierslieu. We combined the two datasets by removing the duplicates to have a total of ~24k tweets.

We then used the spacy French language library (fr_core_news_lg) to extract the n-grams from all tweets. Using the top 10 topic terms, we labeled all tweets from a given year with one topic using two methods
- glove-wiki-gigaword-100 corpus
- A french corpus built on ~600 Million words from french wikipedia (https://fauconnier.github.io/).

## Results

| ![Image](/plots/tweets_topic_time_wiki.jpeg) |
|:--:| 
| Figure 1 shows the first results of our experiment involving tracking the top topic per year as described in the method above. Using the gigaword corpus to train the model, our results showed several emerging trends: the recurrence of the topic “nouveau” in 2011-2012, then the recurrence of the topic “espace” (space) in 2014-2015, and finally the recurrence of the word “territoire” (literally territory, or local area) in 2019-2021. This progression indicates changes in the way tiers-lieux are described by twitter users - first as new projects and methods, then focusing on spaces that they occupy, and finally speaking more about their impact and involvement in local development. This trend would have to be confirmed by further analysis of specific users and correlated to changes in the published literature on tiers-lieux, but does indicate a clear trend. 
 
The total number of tweets increased each year between 2010 and 2019, then dropped off precipitously between 2019-2021. This is likely due to the Covid-19 crisis, since tiers-lieux are working and public spaces and activity was restricted because of the pandemic. |


| ![Image](/plots/tweets_topic_time_french.jpeg) |
|:--:| 
| Figure 2 shows the results of the same experiment as Graph 1 (calculating and tracking the top topic per year) but using the French-language corpus to train the model. The results show a different distribution of topics, which also suggests a trend of change over time, though the topics are different from the model trained on the primarily English-language corpus. In this case, the it is the topic “télétravail” (working from home/out of the office) that rose to the top of the ranking between 2011-2015, then the topic “innovation” in 2015-2016. The topics “numérique” (digital, 2018 + 2020-2021l) and “espace” (space, 2019, 2022) alternated for top ranking in the final years of the analysis. 
 
Interestingly, this progression also indicates changes in the way tiers-lieux are described by twitter users - initially in relation to working-from-home or alternatives to the office, then linked to innovation, and finally to digital policies and spaces. Anecdotally, this tracks with changes in corporate and some public administration discourse around workplace innovation and the rise of working from outside the office thanks to better internet connectivity and changing attitudes towards office hours in France. This trend would have to be correlated by further analysis of specific users, corporate sponsors of sites and changes in the published literature on tiers-lieux, but does indicate a clear temporal trend. Further research could be conducted to understand the specifics of why the topics resulting from the models in experiments 1 and 2 vary so widely.|


Most used hashtags             |  Second-most used hashtags
:-------------------------:|:-------------------------:
![Image](/plots/hashtags_most_used_time.jpeg)  |  ![Image](/plots/hashtags_second_most_used_time.jpeg)|
|:--:|
|This analysis shows the first- and second-most used hashtags associated with tweets that were also tagged with #tierslieux and #tierslieu between 2011 and 2022. Every single year, the most used hashtag was coworking. The second most frequently used hashtag varied nearly every year from 2011 to 2019: coworking, tourtt (“Tour de France de Télétravail, a press tour organised by LMBG Labs, a Paris-based consultancy that created coworking spaces and events), “télétravail”, fablab (another example of corporate jargon used to describe short-term projects geared at innovation, startup incubation and creative projects), biennaledesign17 (in reference to the 2017 Biennale du Design de Saint-Etienne, which was entitled “Working Promesse: Les mutations du travail” (Working Promise: the evolution of work”), “immobilier” (real estate), and finally “ESS” (“économie solidaire et sociale” / social and solidarity economy), signalling a broader shift to messaging about the role of tiers-lieux.|


| ![Image](/plots/tweets_values_carried_year.jpeg) |
|:--:| 
| This plot shows the change over time of the occurrence of values that appear on Twitter (the range of values being limited to those that were also chosen by tiers-lieux to represent themselves on Commune Mesure). We can see a general increase in the number of mentions for almost all of the values over time, with an inflection point in 2019 was due to the decrease in the number of tweets overall due to the pandemic. Two trends stand out: the much more rapid rise of “acceuil” (beginning in 2018) and “partage” (starting in 2016). To understand this phenomenon, we need to look at the context of what sites and users were Tweeting at this time. Was there an increase in the number of sites working on temporary housing (with which these terms are often associated in the language of tiers-lieux)? Or is it just a semantic shift?  |



| ![Image](/plots/tweet_vs_website_combined.jpeg) |
|:--:| 
| In this plot, the values that appear on the x-axis are the most frequent terms that emerge from a specific category of the Commune Mesure corpus: specifically, the “values” chosen by the participating sites to represent themselves. We searched for and plotted the occurrence of these terms in the Twitter corpus. There is a clear divergence between the terms articulated by the 38 Commune Mesure sites and those that appear on Twitter. The most frequently used values on CM (creativité/creativity, coopération and convivialité) were found significantly less frequently on Twitter. There was more significant overlap between two terms – “acceuil” (“welcome” or “hospitality” in the sense of having guests but also extending to temporary housing) and partage (sharing). The term “environnement” is cited less than one third (CM) and one quarter (Twitter) as often as the top two terms but showed significant overlap. |



