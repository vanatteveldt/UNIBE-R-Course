# Data Wrangling and Text Analysis in R

Before we start, [please make sure you have RStudio installed and you have played around with R at least a little bit!](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_basics_1_getting_started.md)

* Daily routine:

We have two sessions per day. Each session has the following routine:

1. Background reading and introductory video (asynchonous)
2. Interactive Q&A (plenary zoom) 
3. Supervised practice session (zoom breakout rooms)

Schedule and materials: (will be updated during the course)
 
+ Monday AM: **Introduction to R & Rstudio**
  + Preparation / background reading: 
    + Install RStudio: [Getting Started](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_basics_1_getting_started.md)  
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf), chs. 1, 2, 3 
    + [R4DS chapter 4](https://r4ds.had.co.nz/workflow-basics.html)
  + 9:00: Video lectures: [introduction to R & Rstudio](https://www.youtube.com/watch?v=PVhZD5MINYM&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=1), [R is fun!](https://www.youtube.com/watch?v=eYCV8kIsgGs&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=2)
  + 10:00: Plenary session: Introduction, Q&A
  + 11:00 - 12:00: Supervised practice: Fun with R ([ch. 2 of CaC](http://cssbook.net/cssbook_draft.pdf)); [Getting Started](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_basics_1_getting_started.md) ; [Data and functions](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_basics_2_data_and_functions.md)
+ Monday PM: **Tidyverse I & II: Importing, Cleaning, and summarizing Data**
  + Preparation / background reading: 
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 6 and 7
    + [R4DS chapter 5](https://r4ds.had.co.nz/transform.html)
  + 13:00: Video lectures: [Importing and Cleaning data](https://www.youtube.com/watch?v=CATqkFiZljU&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=3), [Grouping and Summarizing](https://www.youtube.com/watch?v=lde7wLORQpo&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=4), [Importing Data](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/Gathering_data.md)
  + 14:00: Plenary Session / Q&A
  + 14:30 - 15:30; Supervised Practice: [Transforming Data](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-5-transformation.md) [Summarizing Data](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-5b-groupby.md)
  
+ Tuesday AM: **Tidyverse III & IV: Reshaping and Merging**
  + Preparation / background reading: 
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapter 7
    + [R4DS chapter 12](https://r4ds.had.co.nz/tidy-data.html) and [13](https://r4ds.had.co.nz/relational-data.html)
    
  + 9:00: Video lectures: [Reshaping data](https://www.youtube.com/watch?v=j4lZWJ3Osr8&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=5) & [Joining Data](https://www.youtube.com/watch?v=gg87Nv98VhQ&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=6)
  + 10:00: Plenary session / Q&A
  + 10:30 - 11:30: Supervised practice: [Reshaping Data](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r-tidy-12-reshaping.md), [Merging Data Sets](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-13a-joining.md)
+ Tuesday PM: **Visualization with GGPlot**
  + Preparation / background reading / links: 
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapter 8
    + [R4DS chapter 7](https://r4ds.had.co.nz/exploratory-data-analysis.html)
    + [Data Visualization: A practical introduction (Kieran Healy)](https://socviz.co/)
    + [The R Graph Gallery](https://www.r-graph-gallery.com/)
    + [Data-to-Viz](https://www.data-to-viz.com/)
  + 12:30: Video lecture: [Visualization with GGPlot](https://www.youtube.com/watch?v=wO5mrVaCB28&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=7)
  + 13:30: Plenary session / Q&A
  + 14:00 - 15:00: Supervised practice: [Data Visualization](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r-tidy-3_7-visualization.md)
  
+ Wed AM: **Quantitative text Analysis with Quanteda**
  + Preparation / background reading:
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 10 and 11
    + [Welbers, Atteveldt & Benoit (2017, CMM) Text Analysis using R](http://vanatteveldt.com/p/welbers-text-r.pdf) 
    + [Grimmer & Stewart (2013, PA) Text as Data](http://www.collingwoodresearch.com/uploads/8/3/6/0/8360930/grimmer_and_stewart_2012.pdf)
  + 9:00: Video lecture: [Dealing with textual data](https://www.youtube.com/watch?v=ofOJiuaHV2w&list=PLjXODJ_lGN_V2ntvV2CN_GvzZ6Qm5km9L&index=8), [Quantitative Text Analysis](https://www.youtube.com/watch?v=O6CGXnxPHok&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=1), [Advanced preprocessing](https://www.youtube.com/watch?v=tQoCjVat6UE&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=2), [Demo: Corpus Statistics](https://www.youtube.com/watch?v=7z7U7ORFWQM&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=3) 
  + 10:00: Plenary session / Q&A
  + 10:30 - 12:00:Supervised practice: [Basic String Handling](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R-tidy-14-strings.md), [Quantitative Text Analysis](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_text_3_quanteda.md)
  
+ Wed PM: **Dictionary analysis and Sentiment Analysis**
  + Preparation / background reading:
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 11 and 12.1
    + [Van Atteveldt, Velden & Boukes (2020), Automatic Sentiment Analysis](http://vanatteveldt.com/wp-content/uploads/atteveldt_sentiment.pdf) *(Under review - please do not distribute)*
   + 13:00: Video lecture: [Analysing Text](https://www.youtube.com/watch?v=bHa2CClBYFw&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=4), [Demo: Sentiment Analysis](https://www.youtube.com/watch?v=U0l5GB0i3uU&list=PL-i7GM-A1wBZYRYTpem7hNVHK3hSV_1It&index=5)
   + 14:00: Plenary session / Q&A
   + 14:30 - 16:00: Supervised practice: [Lexical Sentiment Analysis](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/sentiment_analysis.md)
   

+ Thu AM: **Topic Modeling**
  + Preparation / background reading:
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 12.3
    + [Chang et al. (2009) Reading Tea Leaves: How Humans Interpret Topic Models](https://papers.nips.cc/paper/3700-reading-tea-leaves-how-humans-interpret-topic-models)
  +  9:00: Video lecture: [Topic Modeling with LDA](https://www.youtube.com/playlist?list=PLjXODJ_lGN_WtxhPsQ_t0aHtFAcsIh1-8)
  + 10:00: Plenary session / Q&A
  + 10:30 - 12:00: Supervised practice: [LDA in R](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_lda.md) ; [Creating a Topic Browser](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/R_text_topicbrowser.md) 
  + Additional links: 
    + [SVD and dimensionality reduction](https://htmlpreview.github.io/?https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/graphical_interpretation.html)
    + [Computing perplexity](https://github.com/vanatteveldt/learningr/blob/master/topicmodels/perplexity.R) 
    + [Build your own gibbs sampler in R](https://github.com/vanatteveldt/learningr/blob/master/topicmodels/lda_sampler.R) 
    + [Animated Gibbs sampler](https://github.com/vanatteveldt/learningr/blob/master/topicmodels/lda_anim.R) 
    
+ Thu PM: **Structural Topic Models**
  + Preparation / background reading:
    + [Structural Topic Modeling Vignette](https://github.com/bstewart/stm/blob/master/vignettes/stmVignette.pdf?raw=true) (see also [www.structuraltopicmodel.com](http://www.structuraltopicmodel.com))
  + 13:00: Video Lecture: [Variants of Topic Models](https://www.youtube.com/watch?v=3rqkSqKp85s&list=PLjXODJ_lGN_U02yQyZG5YpBgseVpiS9s2&index=2&t=0s) [Structural Topic Models](https://www.youtube.com/watch?v=37yvQdQw5j8&list=PLjXODJ_lGN_U02yQyZG5YpBgseVpiS9s2&index=2)
  + 14:00: Plenary Session / Q&A
  + 14:30 - 16:00: Supervised practice: [Structural Topic Models](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_stm.md)
  
+ Fri AM: **Simple Web Scraping and preprocessing**
  + Preparation / background reading:
    + [Computational Analysis of Communication](http://cssbook.net/cssbook_draft.pdf) chapters 13
  + 9:00: Video lecture: **Web scraping**, **Preprocessing**
  + 10:00: Plenary session / Q&A
  + 10:30 - 12:00:Supervised practice: **Scraping with rvest**, **Accessing social media APIs**, [Linguistic Preprocessing](https://github.com/ccs-amsterdam/r-course-material/blob/master/tutorials/r_text_nlp.md)
+ Fri PM: **Supervised Text Classification**

