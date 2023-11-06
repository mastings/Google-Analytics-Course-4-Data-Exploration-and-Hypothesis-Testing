# Google-Analytics-Course-4-Data-Exploration-and-Hypothesis-Testing
Google Analytics Course 4 Data Exploration and Hypothesis Testing final project

**Background on the TikTok scenario**

At TikTok, our mission is to inspire creativity and bring joy. Our employees lead with curiosity and move at the speed of culture. Combined with our company's flat structure, you'll be given dynamic opportunities to make a real impact on a rapidly expanding company, and grow your career.

TikTok users have the ability to submit reports that identify videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. The process generates a large number of user reports that are challenging to consider in a timely manner. 

TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.

**Your tasks for this project**

You will conduct hypothesis testing on the data for the claims classification data. You’ve been asked to investigate TikTok's user claim dataset to determine which hypothesis testing method best serves the data and the claims classification project.

**Hypothesis testing**

The team looked into the relationship between the verified_status field and the video_view_count field. They did so by first calculating the mean view count for each status as shown in the graphic below. It is clear that videos posted by verified users have, on average, a lot less views.

![Capture](https://github.com/mastings/Google-Analytics-Course-4-Data-Exploration-and-Hypothesis-Testing/assets/22780966/cf12a709-f1f6-4d68-9c6d-c902bf5cc375)

The team then conducted a two-sample t test to determine the significance of the hypothesis. The team found that there is indeed a significant difference. 

**Conclusion**

The analysis found that there is a significantly significant difference in view counts between TikToks posted by verified and unverified users. This suggests that there might be only behavioral differences between the 2 groups. 
