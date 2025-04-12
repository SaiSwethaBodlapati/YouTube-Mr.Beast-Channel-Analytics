# YouTube-Mr.Beast-Channel-Analytics

## Project Overview
A PySpark-powered analysis of MrBeast's YouTube videos to uncover performance patterns and engagement strategies. This project examines:
- Optimal posting times
- Video length impact
- Title effectiveness
- Engagement metrics

## Key Analyses
1. **Posting Schedule Analysis**
   - Best days/hours for maximum views
   - Time-based engagement patterns

2. **Content Analysis**
   - Video length vs. performance
   - Title characteristics (length, keywords)
   - Tag usage patterns

3. **Engagement Metrics**
   - Like/view and comment/view ratios
   - Engagement by video length

## 🛠 Technical Implementation
- **PySpark** for distributed data processing
- **Data Cleaning**:
  - Timestamp standardization
  - Null value handling
  - Duration conversion
- **Advanced Analytics**:
  - Time-based aggregations
  - Engagement scoring
  - Statistical percentiles

## Visualizations
- Views by day of week
- Views by hour of day
- Performance by video length
- Engagement by content type

## Output Files
- `mrbeast_recommendations.txt`: Actionable insights
- Console output of key findings
- Interactive matplotlib visualizations

## Key Findings
1. Optimal posting times (specific days/hours)
2. Most effective video lengths
3. Title characteristics that drive engagement
4. Engagement patterns across content types

## **Conclusion**  

This project successfully uncovers key insights into what makes his content highly engaging and viral. By leveraging **PySpark** for large-scale data processing, we analyzed posting patterns, video characteristics, and audience engagement to derive actionable recommendations.  

### **Key Takeaways**  
**Best Posting Times:**  
   - Videos posted on **{top_day}** around **{best_hours}** tend to get the highest views.  
   - Engagement peaks during specific time windows, suggesting strategic scheduling.  

**Optimal Video Length:**  
   - **{best_length}** videos perform best in terms of views and engagement.  
   - Shorter vs. longer content trade-offs were analyzed for maximum impact.  

**Title Optimization:**  
   - Titles with **numbers** and **dollar amounts** (e.g., *"$1 vs. $1,000,000"*) attract more clicks.  
   - The ideal title length is around **{optimal_title_length} characters**.  

**Engagement Strategies:**  
   - **Like-to-view ratio:** **{avg_like_ratio}%**  
   - **Comment-to-view ratio:** **{avg_comment_ratio}%**  
   - Engagement is highest for **{best_engagement_length}** videos.  

### **Final Recommendations for Content Creators**  
**Post strategically** – Align uploads with high-engagement days/times.  
**Optimize video length** – Focus on the most effective duration range.  
**Craft compelling titles** – Use numbers, money references, and concise phrasing.  
**Boost engagement** – Encourage likes and comments, especially on mid-length videos.  

This analysis provides **data-backed insights** that can help YouTubers refine their content strategy for better reach and engagement. Future work could include **sentiment analysis on titles/descriptions** and **cross-channel comparisons** for deeper insights.  
