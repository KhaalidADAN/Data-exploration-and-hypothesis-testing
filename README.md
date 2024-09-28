# TikTok Claims Classification Using Regression Models

## Project Overview
This project focuses on building a machine learning model to classify claims from TikTok user submissions. We analyzed the relationship between verified status and video view count to uncover potential behavioral patterns. Our initial hypothesis test suggests significant differences between verified and unverified TikTok accounts regarding view counts.

## Business Understanding
The TikTok data team aims to improve the efficiency of claim classification by understanding how verified and unverified accounts behave differently.

**Stakeholders:**
- TikTok Data Team
- Content Moderation Department

The business objective is to create models that will help classify user claims more effectively by leveraging insights from user behavior.

## Data Understanding
The data includes:
- **Verified Status** (categorical: verified/unverified)
- **Video View Count**

### Key Findings:
- Unverified accounts have an average of **265,663 views**, while verified accounts average **91,439 views**.

### Limitations:
- The analysis only explored quantitative data related to view counts. Factors like engagement rates and content type were not considered, which may have influenced the view counts.

## Modeling and Evaluation
Our initial modeling approach includes a regression model focusing on verified status to analyze its effect on video views. This foundation will support further development of a claim classification model.

### Model Results:
- A two-sample hypothesis test showed a statistically significant difference in video views between verified and unverified accounts, confirming that unverified accounts tend to have higher view counts.

## Conclusion
The analysis reveals behavioral differences between verified and unverified accounts, which is critical in shaping future claim classification models.

## Next Steps:
- **Build Regression Model:** Focus on user behavior based on verified status to enhance claim classification.
- **Further Investigation:** Explore why unverified accounts garner more views and whether they are linked to spam bots or more engaging content.
