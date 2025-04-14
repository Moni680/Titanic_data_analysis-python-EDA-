# Titanic_data_analysis-python-EDA-

"The RMS Titanic — a ship of dreams — set sail in 1912, carrying over 2,200 people. But when it struck an iceberg, only about a third of the passengers survived. What made the difference between life and death? Let's dive into the data and find out."
<br>
🚢 Chapter 1: The Data Voyage Begins
<br>
We began our journey by loading the Titanic dataset — a snapshot of 891 passengers, recording details like age, gender, class, and whether they survived the disaster.
<br>
Before jumping into insights, we cleaned the deck:
<br>
Filled in missing age values using the median.
<br>
Replaced missing embarked entries with the most common port.
<br>
Dropped the Cabin column due to too many missing values.
<br>
Created useful features like FamilySize, IsAlone, and grouped Age into meaningful categories.
<br>
👀 Chapter 2: Who Survived?
<br>
A quick glance at survival numbers showed that:
<br>
Only 38% of passengers survived.
<br>
## This begged the question: who were these survivors?
<Br>
👩‍🦰 Chapter 3: Women and Children First
<br>
The data confirmed the age-old saying:
<br>
74% of women survived, compared to only 19% of men.
<br>
Children (age < 12) had the highest survival rate, especially in 1st and 2nd class.
<br>
Teenagers and young adults faced higher risk if they were male and in lower classes.
<br>
💡 Insight: Gender and age clearly influenced rescue priorities.
<br>
🎩 Chapter 4: Class Matters
  <br>
We saw the harsh reality of the class divide:
<br>
1st class passengers had the highest survival rate (~63%).
<br>
3rd class passengers faced the lowest chances (~24%).
<br>
💡 Insight: Those with higher socioeconomic status were more likely to reach lifeboats in time.
<br>
🧍‍♂️ Chapter 5: Traveling Alone vs. With Family
  <br>
Passengers traveling alone had significantly lower survival chances than those with family on board.
<br>
FamilySize = 0 → lower survival
<br>
Moderate family size (1–3 members) saw better outcomes

💡 Insight: Being part of a small group might have improved communication and coordination during evacuation.

📊 Chapter 6: Age Group Visualization
We visualized survival by age groups:

Children (0–12) were clearly prioritized.
<br>
Young adults had mixed survival rates depending on class and gender.
<br>
Seniors (60+) had very low survival overall.
<br>
These visualizations brought empathy to the data — we could see who had a better chance, and who didn’t.
<br>
🔎 Chapter 7: What the Numbers Say
The correlation heatmap told a final tale:
<br>
##Survival was positively correlated with Fare and being female.
<br>
##It was negatively correlated with Pclass and being alone.

