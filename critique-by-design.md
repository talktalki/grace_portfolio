| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique By Design

## I. Original Visualization
As an international student myself, I have always been interested in the enrollment of international students in the US and the breakdown of the numbers by country. Below is a visualization titled "By the Numbers: Who Sends the Most Students to Study in the U.S.?" as part of an article that provides a guide to the international students who plan to study in the US. The article uses _Open Doors_ as its source of data, which has long been regarded as the information resource on international students in the United States. 

![Original Visualization](study-in-the-US.png)
- Source: https://www.affordablecollegesonline.org/international-students-guide-studying-in-usa/

I will critique this visualization and create a redesign to improve on some of the aspects that could be worked on.

## II. Critique

| Category       | Score | Notes |
| -------------- | ----- | ----- |
| Usefulness     |   5   | The information is useful and relevant, but it's basic in that it only presents numbers. One could use the same data to highlight other aspects of the data to derive more interesting insights. |
| Completeness   |   6   | There are a lot of colors. Between the pie chart and the table, the author indicated the matching color from the pie chart on the left side of the table, but because there are too many colors, it’s difficult to keep track which color indicates which country. |
| Perceptibility |   6   | Using a 3D pie chart is not recommended as it can distort the size of the area in the pieces, and therefore wrongly represent the values of each piece. For instance, 31% in red looks much bigger than 30.9% in blue, even though it’s only 0.1% difference. |
| Truthfulness   |   4   | When comparing the dataset and the visualization, I found that the number of students for China is actually incorrect! It must have been a typo. This is significant mistake that hurts the visualization's credibility. |
| Intuitiveness  |   8   | The table and pie chart is pretty intuitive and easy to interpret. |
| Aesthetics     |   6   | The visualization is simple but not exactly beautiful/pleasing to look at. Especially because there are too many colors, it might be more confusing than aesthetically pleasing. |
| Engagement     |   7   | Again, the visualization shows relevant data - current message is to show the lead countries of origin for international students. However, I think the author could do a little better to further develop the key message in order to encourage the audience to explore more about the topic. Right now, the visualization shows the top 10 countries in the world with most international students in the US, but it ends there. For example, the visualization could tell a story about how the numbers changed for each country before and after the pandemic. (Key message: the number of foreign students studying in the United States fell sharply during the 2020/21 academic year) I would also update the data to represent the most relevant academic years as of now. |

## III. Initial Sketch
![Sketch](sketch.jpg)

## IV. User Feedback
- Feedback #1 by mid-20's male student:
1) The message is clear. It is a visualization that shows percentage of students decreasing during the covid period but has since picked up.
2) Would like to see the magnitude of the change (include percentage values)
3) Think about the intended audience. Is it people in the education industry? Could be the government?

- Feedback #2 by mid-20's female student:
1) Confused as to what the starting point is for each period.
2) Add pop-up that shows the raw count as well (in order to prevent misleading perceptions of the magnitude of the count)
3) Might want to develop a specific point/story to highlight using the visualization
4) Dont' spread out the labels of the countries too much - try to keep the gaps in scale so that the user has a better idea of the differences between countries
5) Change color scheme to something other than green/red to account for colorblindness.  
  
## V. Redesign
<div class="flourish-embed flourish-slope" data-src="visualisation/15067570"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Now in this redesign, rather than showing the raw numbers, I show the percentage change between consecutive academic years divided into three periods: pre-covid, during covid, and post-covid. This design is intentional because I want to convey the message: enrollment of international students in the US significantly decreased right after covid hit, and has increased since then. 

The intended audience for this visualization could be the admissions office, the government or anybody who's interested in knowing the makeup of international students in the US as well as the trend over years. However, I do think that they need to have a good understanding of the concept of percentage change in order to understand this chart to the fullest extent.

While in the process of redesigning, I noted there are limitations with the Flourish platform. For example, I wanted to color the background of the chart with different colors to differentiate the positive range and the negative range. However, Flourish only offers one choice of color to color the background. Another important part of the chart was to label the y-axis (0% at the initial node) but I couldn't do that with Flourish. Here is a screenshot of a version that includes this aspect. 
