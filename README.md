# metacriticshills
Identify and shame the bad shills

1. Calculate Review Score Discrepancy

    Mean Discrepancy Analysis: Calculate the average score of user reviews and the average score of critic reviews. The larger the discrepancy between the two, the more likely it is that critic reviews are biased.
    Variance Analysis: Look at the variance of scores in both critic and user reviews. If critic scores are tightly clustered around a high score with little variance while user scores show wider variance (often lower scores), this could indicate unnatural inflation.

2. Sentiment Analysis on Textual Reviews

    Use natural language processing (NLP) techniques to analyze the sentiment of the review text. If critic reviews have overwhelmingly positive language compared to user reviews, this may indicate bias.
    Outlier Detection: Identify reviews with highly positive language and compare these to the typical sentiment distribution in critic and user reviews. Outliers with extreme positivity in the face of negative user feedback might be flagged as suspect.

3. Time-Based Analysis

    Early Reviewer Bias: Some shill reviews may appear earlier than user reviews to set a positive tone. By calculating the time distribution of positive critic reviews versus user reviews, you can identify if most high ratings were front-loaded (possibly from paid reviewers).
    Decay Pattern: Genuine reviews might show a natural decline in scores over time as more people evaluate the game critically. If critic reviews maintain consistently high ratings while user reviews decline, this can be another red flag.

4. Comparison with Historical Reviewer Data

    Reviewer Consistency: Check if certain reviewers consistently rate all products from a specific developer or publisher much higher than other critics. Reviewers who always rate these games highly, regardless of user scores, may be shills.
    Genre-Agnostic Reviews: Critics who rate games very differently from their usual genre preferences (e.g., a reviewer known for FPS games giving an unusually high score to a fantasy RPG) might also indicate bias.

5. Detect Paid Review Patterns through Clustering

    Use clustering algorithms (like k-means) to group reviews based on score and sentiment features. Shill reviews might cluster separately due to their unique features (extremely high scores, positive sentiment, early posting time) compared to regular critic reviews.
    Cluster Purity Check: If clusters with higher scores correlate disproportionately with early review dates or known reviewers, they could be suspected shills.

6. Identify Extremes in Reviewer Language and Tone

    Lexical Analysis: Shill reviews may use overly positive adjectives (e.g., “groundbreaking,” “flawless”) more frequently than user reviews or even genuine critic reviews. NLP tools can help calculate the frequency of such terms and identify abnormally positive or exaggerated language.
