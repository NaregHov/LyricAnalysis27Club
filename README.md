# LyricAnalysis27Club
In recent years, many of our favorite artists have been telling stories of their mental states as well as personal stories. Rapper Mac Miller wrote about his drug usage, which foreshadowed his death in 2018. Mac Miller, Lil Peep, Avicii, and Chester Bennington are just some contemporary artists whose personal struggles (expressed through their music) and untimely demises have created shockwaves across the industry. But this trend has roots in incidents that reach back to at least the 1970’s, with the formation of the infamous 27 Club. Janis Joplin, Jimi Hendrix, Jim Morrison, and many others have contributed in creating an almost cult-like reverence for the tragic ending of a musician’s life via their own demons and vices. The struggles of modern musicians and the long history of overlooking their underlying issues inspired us to look at whether or not lyrical analysis of their works and activities can help predict self-harm behavior for artists in the future.

# Introduction

In recent years, many of our favorite artists have been telling stories of their mental states as well as personal stories. Rapper Mac Miller wrote about his drug usage, which foreshadowed his death in 2018. Mac Miller, Lil Peep, Avicii, and Chester Bennington are just some contemporary artists whose personal struggles (expressed through their music) and untimely demises have created shockwaves across the industry. But this trend has roots in incidents that reach back to at least the 1970’s, with the formation of the infamous 27 Club. Janis Joplin, Jimi Hendrix, Jim Morrison, and many others have contributed in creating an almost cult-like reverence for the tragic ending of a musician’s life via their own demons and vices. The struggles of modern musicians and the long history of overlooking their underlying issues inspired us to look at whether or not lyrical analysis of their works and activities can help predict self-harm behavior for artists in the future.

# Prior Work
We have identified 4 prior works related to our topic who have approached various aspects of our planned project.
Crime Rates versus Crime Lyrics by Emmanuel Khodra
Khodra’s project focuses on investigating whether there really is a strong correlation between an increase in lyrics containing references to criminal activities and an increase in related crimes. Khodra’s use of visualizing data is an excellent example for us of juxtaposing different correlations efficiently.
The Influence of Rap/Hip-Hop Music: A Mixed-Method Analysis on Audience Perceptions of Misogynistic Lyrics and the Issue of Domestic Violence
This study focused on examining misogyny in hip hop lyrics using Qualitative Content Analysis and Cultivation Theory. While not explicitly related to data science, its qualitative methods are useful for performing in-depth abstract analyses of the correlations we’d like to explore.
The Largest Vocabulary In Hip Hop
Daniels’ project maps out prominent rappers with the largest vocabulary in their given volume works. Its use of token analysis and reducing bias by limiting every measured artist to a reasonable benchmark can help us in analyzing various artists’ lyrics by accounting for vernacular and addressing the potential bias of varying levels of fame.

# Data Cleaning and Results
https://docs.google.com/document/d/1LUmmj38EjYK4_Vtd9jg9GSRkeeMR7XjLXfherKfIkrM/edit

# Privacy Concerns
Our dataset mainly draws from wikipedia tables, supplemented with the “Every Song You Have Heard (almost!)” dataset from Kaggle. These datasets, unless specified, are considered free to use for the public. Wikipedia info is permissible for use by the public under the Wikimedia Creative Commons license. This also answers any possible privacy issues that could have arisen for us. For the Kaggle dataset, lyrical content is published on the web with permission from artists. There is a csv file crediting all URLs where lyrics are taken from as well.
The most apparent bias within our dataset, would be the overrepresentation of famous/celebrity artists. Many artists whose lyrics we will choose to analyze are celebrity artists, since more people are more familiar with their work, as a general rule of thumb. They are not entirely representative of the average artist or musician. Celebrity artists’ lifestyles may add bias to our data because their increased popularity leads to intensified scrutiny under the public eye, possibly leading to altered behavior, compared to the average artist. Furthermore, our study will touch on a sensitive topic of mental health. Although the project will be looking at the matter of mental health objectively, we are still going to be examining subjects from an individual’s personal life. To avoid this, we have made sure our analysis is based solely upon the data that we have, and have focused on the relationships between lyrical content, cause of death, and words that are indicative of current mental health.

# Analyzing Results
For the sake of our study, let us assume that artists who are still alive or died of non-drug related charges are likely to have strong mental health and wellness in addition to higher scores, displaying lyrics that are more positive and artists who aren’t alive or died of drug related charges are likely to have mental health and wellness issues in addition to lower scores, displaying lyrics that are more negative.
We found 23 artists that have high correlation with our hypothesis, 11 with more positive lyrics and 12 with more negative lyrics.


Strong correlation (23/57) (Average: 0.547693) (Average age: 61.82)

Artist who are alive

Bobby Brown: 0.644654
Alive(50); cocaine, credits sobriety to not wanting to go back to jail

Brian Wilson: 0.554533
Alive(76); history of LSD use

Britney Spears: 0.442178
Alive(37); alcoholism, rehab, crew banned alcohol

Donovan: 0.416699 Alive(72); recreational cannabis use

Elton John: 0.377940 Alive(71); cocaine, was able to get sober

Keith Urban: 0.610 Alive(51); credits wife for sobriety

Among those 11 artists with positive lyrics, 6 are still alive (average age: 59.5), crediting sobriety to their long-lasting success.

Britney Spears, who has struggled with alcoholism, was finally able to get sober after multiple stints in rehab and those around her have taken measures such as banning alcohol on tours to maintain her success. Bobby Brown, who has battled cocaine addiction for years, says imprisonment was the final straw and was able to reach sobriety, citing never wanting to go back to jail as motivation. Lastly, with the help of his wife, Keith Urban was able to free himself from drug and alcohol addiction.

Died of Non-Drug Related Deaths

Louis Armstrong: 0.501
Died at 69; heavy cannabis use, heart attack

Natalie Cole: 0.684
Died at 65; heart attack

Ray Charles: 0.474
Died at 73; liver disease

Rick James: 0.7877
Died at 56; heart attack, drug use, periods of sobriety

Syd Barrett: 0.531924
Died at 60; pancreatic cancer, psychedelics

The other 5 artists with positive lyrics had an average lifespan of 64.6 years, with deaths unrelated to alcohol or drug abuse.

Drugs are prevalent in the music industry. Even though each of these 5 artists has battled their fair share of drug addiction, they have also had long periods of successful sobriety. Louis Armstrong was a heavy cannabis user who ultimately died of a heart attack at 69 (unrelated to drugs), having said cannabis is “a thousand times better than whiskey” (Andrews, E. (2016, August 04)). Like Armstrong, Natalie Cole died at 65 and Rick James at 56 of a heart attack. Syd Barrett’s life was lost to pancreatic cancer at 60.

Negative (History of drug abuse/died of drugs) (Average: 0.049994) (Average age of death 42)
Chris Cornell: 0.052960
Died at 52; suicide by hanging

Esther Phillips: 0.331003
Died at 52; liver/kidney failure, drug abuse

Gary Moore: 0.183071
Died at 51; Alcohol poisoning

Jim Morrison: 0.143940
Died at 27; Heart attack (drug related)

Jimi Jamison: -0.953100
Died at 63; Stroke (Drug related)

Johnny Thunders: 0.081455
Died at 38; Drug-related

Mac Miller: -0.09
Died at 27; overdose

Paul Butterfield: 0.306
Died at 44; overdose

Phil Lynott: 0.032
Died at 36; heart failure

Scott Weiland: 0.027227
Died at 48; overdose

Sid Vicious: 0.260917
Died at 21; overdose

Vic Chesnutt: 0.224449
Died at 45; overdose

Among those 12 artists with lower scoring lyrics, all have died as a result of overdose, suicide, or drug-related causes.
7 of the 12 deaths were a direct result of drug overdose or alcohol poisoning while 5 of the 12 were indirectly drug-related (liver/kidney failure, heart attack, stroke, hung himself). The average lyric score of these artists was 0.049994 and lifespan of 42 years.

We note a significant difference in lyric score and lifespan between artists who are alive/died of non-related drug issues (lyric score 0.547693, average lifespan of 61.82 years) and artists who died of drug issues (lyric score 0.049994, average lifespan of 42 years), a lyric score difference of 0.497753 and lifespan of 20 years. Through lyric analysis, we can predict which future artists are high-risk for self-harm and raise awareness as fans to hopefully improve their quality of life and music.

Some correlation (23/57) (Average: 0.419960) (Average age: 47.52)

Among artists who we have determined have some correlation, we can create further subdivisions that would provide more insight into their lyric score. This group of artists in the middle with some correlation was determined by chronic drug use, spanning multiple decades, with no admittance of sobriety or rehab stints. It is in between our primary group and outliers.

Similar to the group of artists who displayed strong correlation, we took our group of 23 and divided it into two. Let us assume artists who are still alive or died of non-drug related reasons are likely to have strong mental health and wellness in addition to higher scores, displaying lyrics that are more positive (of which there are 9) and artists who aren’t alive or died of drug related reasons are likely to have mental health and wellness issues in addition to lower scores, displaying lyrics that are more negative (of which there are 14).

Positive (Alive/Died of Non-Drug Related Causes) (Average: 0.3928) (Average age: 61.55)

Bob Marley: 0.341659 (skin cancer; 36)
David Bowie: 0.154884 (liver cancer; 69)

George Harrison: 0.500682 (heart attack; 58)

Jerry Garcia: 0.421189 (heart attack; 53)

Gerry Rafferty: 0.570852 (heart attack; 63)

Michael Jackson: 0.421 (heart attack; 50)

Neil Young: 0.384 (alive; 73)

Tom Petty: 0.463397 (heart attack; 66)

Yoko Ono: 0.277256 (alive; 86)

Among those 9 artists who are alive or died of non-drug related causes lyrics (average age: 59.5), the average lyric score was 0.3928 and the average age was 61.55 years.

In particular, the 2 who are still alive, Neil Young (lyric score of 0.384, age 73) and Yoko Ono (lyric score of 0.277256, age 86) have been listed as having some correlation instead of strong due to their low lyric scores despite their long lives.

Negative (History of drug abuse/died of drugs) (Average: 0.437440) (Average age: 38.5)

Amy Winehouse: 0.330705 (alcohol poisoning; 27)

Bon Scott: 0.190650 (alcohol poisoning; 33)

David Ruffin: 0.573835 (overdose; 50)

Dee Dee Ramone: 0.438300 (overdose; 50)

Dinah Washington: 0.532280 (overdose; 39)

Jimi Hendrix: 0.444076 (overdose; 27)

Judee Sill: 0.567135 (overdose; 35)

Kevin Dubrow: 0.369 (overdose; 52)

Nick Drake: 0.528 (suicide; 26)

Prince: 0.553 (overdose; 57)

Tim Buckley: 0.380397 (overdose; 28)

Tim Hardin: 0.479188 (overdose; 49)

Tommy Bolin: 0.458900 (overdose; 25)

Tony Sly: 0.278700 (overdose; 41)

Among the 14 artists that were a direct result of drug overdose or alcohol poisoning, the average lyric score of these artists was 0.437440 and lifespan of 38.5 years.

In this sample, we note virtually no difference in lyric score between artists who are alive/died of non-related drug issues (lyric score 0.3928, average lifespan of 61.55 years) and artists who died of drug issues (lyric score 0.437440, average lifespan of 42 years), a lyric score difference of only 0.04464. This is significantly lower than the difference between artists with high correlation (0.497753). Interestingly, the difference in average lifespan is similar. The difference amongst artists with high correlation was 20 years while the difference amongst artists with some correlation was 19.45.

Weak correlation (i.e. outliers) (11/57)

Positive, Dead (Average: 0.772647)

Billy Mackenzie: 0.991200 (overdose; 39)

Frankie Lymon: 0.504580 (overdose, 26)

Gram Parsons: 0.490447 (overdose; 26)

Ike Turner: 0.829185 (overdose, 76)

Jesse Ed Davis: 0.958500 (overdose; 43)

Keith Moon: 0.822371 (overdose; 32)

Lowell George: 0.928 (overdose, 34)

Whitney Houston: 0.656898 (overdose; 49)

Negative, Alive (Average: -0.08732)

Izzy Stradlin: 0.163120 (alive(56); history of drug abuse)

Ozzy Osborn: -0.19 (alive(70), history of drug abuse)

Snoop Dogg: -0.235080 (alive(47), history of drug abuse)

For every rule, there is an exception. In our case, we have 11. In particular, 8 of the 11 who died of an overdose had an average score of 0.772647, which indicates a large amount of positivity in their lyrics. By our measure, these artists live (or had lived) long, drug-free lives with little to no mental health issues. However, this is not the case. Sadly, all 7 artists’ lives were lost to suicide or drug overdose in their 20s to 40s (average age of 35.57 years old).

Perhaps the most interesting case of the 7 is Billy Mackenzie, who has been described as naturally outgoing and extraverted (Mack, the Life: The Psychology Of Billy Mackenzie and The Associates). It was not until the death of his mother that those around him described a noticeable change in his demeanor. During the last few months of his life, Mackenzie was diagnosed as clinically depressed and would succumb to a prescription drug overdose in his father’s shed.

Mackenzie’s case leaves room for in-depth analysis. While the means of doing so are not available to our group, it is worth analyzing Mackenzie’s lyrics of the songs he made between the time of the death of his mother and his suicide. Our prediction is that they would be low/negative. Had the death of Mackenzie’s mother not led to his suicide, Mackenzie would otherwise be another case of strong correlation. For the future, we believe analyzing lyrics down by time specific time periods (week/month/year/etc.) and cross-referencing them with events in the artist’s life would yield near 100% correlation.

The other 3, with an average score of -0.08732, are examples of weak correlation (average age of 57 years old). Despite all 3 having a heavily documented history of drug abuse, they are alive. This raises another limitation in our study. Because we are sorting artists by quantitative data, there is qualitative data we do not have access to that would help us draw conclusions. Even though these artists who are alive have scores that are a lot lower than other artists who died to suicide or overdose, the quality of their life is difficult to express in our research. They could be functioning members of society or (more likely than not) struggle to maintain their mental health on a day-to-day basis.

# Conclusion
We discovered that the majority of the artists who showed position emotions in their songs have a dark history of drug use and drug overdose that often lead them to their death. Even when their songs are happy and positive, it shows that there is no relationship between their drug use and their song lyrics.
