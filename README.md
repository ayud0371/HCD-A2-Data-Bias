# HCD-A2-Data-Bias
In this project, I will be exploring the concept of bias through querying the Perspective API released by Google Jigsaw


Documentation about my analysis:
  I am testing the differences between comments labeled as a 'threat' and comments labeled as an 'insult'
  
  My hypothesis is that Perspective will make mistakes on passive aggressive toxic comments and rate them with a lower toxicity score even if they are just as harmful as the straightforward, agressive comments.

  My results show that the 'threats' label had many more false positives than the 'insult' label, but when looking at false negatives, it is the opposite. I think Perspective rates insults as having lower toxicity scores sometimes, though they can be just as bad as threats
  
