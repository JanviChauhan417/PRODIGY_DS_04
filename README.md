# PRODIGY_DS_04

🎯 Objective:
Understand public opinion toward different brands/entities based on sentiment (Positive, Negative, Neutral) from social media (e.g., tweets).

🔍 What the Visual Shows:
  You’ve used four different visualizations to break down sentiment:

📊 Count of ID by Entity (Top-Left Bar Chart)
  Shows the number of social media posts (tweets) mentioning each brand/entity.
  Insight: Some brands like CallOfDuty, CS-GO, and AssassinsCreed are discussed more frequently.

📊 Count of ID by Entity and Sentiment (Top-Right Stacked Bar Chart)
  Sentiment is broken down for each entity: how many tweets are Positive, Negative, or Neutral.
  Insight: You can compare brand sentiment directly—for example, Microsoft has mostly positive mentions while CS-GO has more negative ones.

🍩 Donut Chart – Count by Sentiment and Entity (Bottom-Left)
  Gives a percentage-based view of sentiment across all entities.
  Insight: Helps you understand the overall tone of public opinion—what % is Positive vs. Negative vs. Neutral.

🧱 Tree Map (Bottom-Right)
  Shows Entity-Sentiment combinations by volume.
  Larger blocks = more mentions.
  Insight: You can immediately spot which brand and sentiment combinations are most prevalent (e.g., Positive–CallOfDuty, Negative–CS-GO).

📈 How to Build These Visuals (Step-by-Step)
🔸 In Excel:
Import your dataset (CSV/Excel).
  Create a Pivot Table:
  Rows: Entity
  Columns: Sentiment
  Values: Count of Tweet ID

Use:
  Bar/Column Charts: for counts per entity/sentiment.
  Pie/Donut Charts: for percentage sentiment.
  Conditional Formatting or TreeMap (Insert > Treemap): for sentiment weight.

🔸 In Power BI: Load Data:
  Get Data > CSV/Excel

Build Visuals:
  Bar Chart: Axis = Entity, Value = Count(ID)
  Stacked Bar Chart: Axis = Entity, Legend = Sentiment, Value = Count(ID)
  Donut Chart: Legend = Sentiment, Values = Count(ID)
  Tree Map: Group = Entity & Sentiment, Values = Count(ID)

Customize:
 Use data colors for sentiment (e.g., red = negative, green = positive).
 Add filters for Date, Entity, or Sentiment.
 Add slicers to allow users to explore data interactively.

📊 Interpretation & Insights You Can Draw:
  Public sentiment can vary widely by brand.
  CallOfDuty has a high volume of positive sentiment.
  CS-GO and Amazon may have higher negative sentiment—potential flags for reputation teams.

  Screenshort/ Demo:
  show what the dashboad look like:
  link: https://github.com/JanviChauhan417/PRODIGY_DS_04/blob/main/task%204.JPG

Microsoft stands out as having a strong positive sentiment.

Neutral mentions could indicate brand visibility but not strong opinions.
