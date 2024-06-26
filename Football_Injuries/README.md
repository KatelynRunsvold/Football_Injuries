Football Injuries
Project 1 Proposal and Analysis

Team Members: Jon M, Eric M, Tyler B and Katelyn R

Project Proposal: Analysis of Football Injuries

Project Description
The primary aim of this project is to analyze the patterns and determinants of injuries in football, focusing on various positions, severity progression throughout the season, and potential correlations with player attributes such as jersey numbers. This research will help identify high-risk positions, understand injury severity trends, and evaluate the impact of player attributes on injury rates, ultimately guiding strategies for improving player safety and performance.

Hypothesis

Position-Based Hypothesis: Wide receivers have the highest rate of injuries compared to other positions in football.

Seasonal Severity Hypothesis: The severity of injuries increases as the football season progresses.

Concussion Risk Hypothesis: Specific positions, such as wide receivers and cornerbacks, are at a higher risk for concussions.

Jersey Number Hypothesis: There is a significant correlation between a player’s jersey number and their injury rate.

Null Hypothesis
Position-Based Null Hypothesis: There is no significant difference in the injury rates among different football positions.

Seasonal Severity Null Hypothesis: The severity of injuries does not change as the season progresses.

Concussion Risk Null Hypothesis: There is no significant difference in the concussion risk among different football positions.
Jersey Number Null Hypothesis: There is no significant correlation between a player’s jersey number and their injury rate.

Process:
Create repository and branches for development
Identify database
Pull in and clean/process data for usability:
Download csv files for each week of NFL 2023 season data
Combine weekly files into single encompassing csv
Clean data by removing duplicate entries, null values, and renaming typos 
Run data manipulation based on individual question work and necessities 
Push updates and completed work to main branch

Analysis:
Data Collection and Descriptive Statistics:

Collect data on injuries from football games, categorized by position, type of injury, and timing within the season.

Use descriptive statistics to summarize the frequency and distribution of injuries.

Position-Based Injury Analysis:
Compare injury rates across different positions
Focus on the most injured positions (e.g., wide receiver, cornerback) to understand specific risk factors.

Seasonal Progression Analysis:
Track the severity of injuries over the course of the season.
Use regression analysis to determine if there is a trend in increasing injury severity.

Concussion Risk Analysis:
Identify positions with the highest number of concussions.
Use logistic regression to assess the risk of concussion for each position.

Jersey Number Correlation:
Calculate the correlation coefficient between jersey numbers and injury rates.
Perform a regression analysis to evaluate the strength and significance of this correlation.


Conclusion:
The expected outcomes of this research include identifying the positions with the highest injury rates, understanding how injury severity changes throughout the season, assessing the concussion risks associated with different positions, and determining if a player’s jersey number influences their injury risk. These insights will inform coaching strategies, training programs, and safety protocols to enhance player health and performance.

Ultimately, this research aims to contribute to the development of targeted interventions that can reduce injury rates and improve the overall safety and success of football teams


Analysis Reporting by Target Question: 
Note: Our analysis begins with our 2nd question from the original proposition.
 
Question 2: 

Injury rate per position provides insights into the risks associated with different roles within a team. We will be able to guide decisions aimed at improving player safety, performance, and overall team success.
Wide Receiver running in high-speed collisions and tackles, leading to various injuries including concussions, hamstring, knee, shoulder and ankle

<img width="581" alt="Screenshot 2024-06-17 at 7 08 46 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/c6cddd62-49c5-4b37-bfcb-990d2ea1e46e">

 
Question 3: Does jersey number have any relation to injury rate?
 
The relationship between a player's jersey number and being injured is relatively weak; however, the statistics (r-value = -0.282935 show us that players with a higher jersey number have a slightly lower chance of being injured. The variability is fairly high across the board with the standard deviation of 14.3. As a result, we have deduced that position is a better indicator of the likelihood of being injured.

<img width="1035" alt="Screenshot 2024-06-17 at 7 07 45 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/0cae9d5b-2aa7-44b0-97b1-b6873dd52da3">


<img width="419" alt="Screenshot 2024-06-17 at 7 48 05 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/a795698f-6aee-4233-a370-845f13be2eeb">

 
Question 4: Which position has the highest chance of being concussed?
 
Concussions offer another important safety concern and area of our focus. To better understand where the greatest risk of concussion occurs, I analyzed our football injuries database to breakdown concussions by positions. By pulling this injury specifically and creating a data frame by position, I was able to create a pie chart that visualizes the relationship. A pie chart helps visualize the breakdown of concussions by injury in a helpful way, as we can clearly see the sizes of each slice. Surprisingly, we see concussions are a widespread issue across multiple positions. While I had expected to see a single position dominating most concussion injuries, it turns out many are susceptible to the risk. The positions with the highest frequencies of injury have been pulled from this data set as well. Also shocking to see wide receivers leading another category of injury. Of the top 5 positions with the highest counts, Wide Receivers made up the largest slice of the pie, having 16.5% of the total number of concussions. Cornerbacks made the second most at 13.4%, Linebackers at 12.4%, Tight End at 10.3% and Offensive lineman at 9.3%. This data gives us an initial idea of where to target our concussion interventions and can provide for historical data to compare against in the feature should changes to help reduce these numbers be implemented.
 
<img width="623" alt="Screenshot 2024-06-17 at 7 08 06 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/327f0f9d-b002-4382-992e-e6313f7699a0">

 
Question 5: Which types of injuries are most common?
 
While concussions are a very important injury, it was important to our analysis to look at total possible injuries as well. Through manipulation of our data set, I was able to get values for each injury type that occurred in the 2023 NFL season. With this information, it was possible to pull numbers of each unique instance of the occurrences of these injuries and generate a bar chart to visualize these counts and injury types. I prepared the chart in order of most to least counts to quickly identify the top occurring injuries from the season. The top 5 most occurring injuries were found to be 1. Knee, 2. Ankle, 3. Hamstring, 4. Shoulder, 5. Concussion. 

<img width="1022" alt="Screenshot 2024-06-16 at 10 03 02 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/c612af65-c099-458a-8aaf-543ecb750808">

Shown to have highest rates of injury, it was further explored to see how wide receivers were getting hurt so much. By drilling down on injury types specific to the WR position, we can get a better idea of injury areas to focus on. From here we can see a need for targeting knee, ankle, and hamstring injuries specifically.

<img width="1061" alt="Screenshot 2024-06-16 at 8 54 05 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/97a45ee8-9677-403b-b40f-7f00a625aa82">

Question 6: Do more injuries occur and does the type of injury change as the season progresses?

<img width="520" alt="Screenshot 2024-06-17 at 7 08 16 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/b198f091-6815-4b58-862a-0ab57f7bc2b9">

<img width="493" alt="Screenshot 2024-06-17 at 7 08 23 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/aa6a4775-0ebc-4022-b307-08edf4c1cffc">

 
There are more injuries as the season progresses but there is no change in the type
 
Question 7: Which teams have the most injuries?
 
Performance Management: Helps coaches and medical staff to improve training and recovery strategies based on injury trends.

Comparative Analysis: Facilitates comparisons between teams and seasons to assess changes in injury rates and effectiveness of injury prevention measures.

<img width="600" alt="Screenshot 2024-06-17 at 7 07 56 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/de03fd47-0871-4cd8-a17d-bd27356ace56">


Question 8: Does the severity of injuries get worse as the season progresses?
 
The percentage of out vs questionable is steady throughout the season so there is no relation

<img width="622" alt="Screenshot 2024-06-17 at 7 08 32 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/f231111f-a3a6-45c8-959c-11408ab1413f">

<img width="385" alt="Screenshot 2024-06-17 at 7 08 37 PM" src="https://github.com/JMiceli7/Football_Injuries/assets/139254725/a9fc862a-e8e3-4944-b294-47ef32e6d145">


