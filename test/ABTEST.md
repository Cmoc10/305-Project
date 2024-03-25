A/B Test Name:
User Story Number:
Metric (from the HEART grid):
Hypothesis: The key part of a A/B test is formulating your hypothesis as this guides the whole A/B test plan. What problem are we trying to solve? Its impact? (e.g. how big this problem is to our customers?) In formulating the hypothesis, first you need to define the problem you want to solve. For example, you are an SaaS that offers free trial and you want to improve Adoption. But that problem might be too broad to form an A/B test as you can simply test one variable in an A/B test to be effective (otherwise you won’t know which variable is causing the change). So to narrow down the problem you want to solve, you need to find out the bottle-neck in the conversion funnel – where do people drop off the most? Are there any key information or call-to-action buttons that you expect people to read/click but they didn’t? 

After narrowing down the problem you want to solve, you then need to make a hypothesis as to what causes those bottlenecks and what you can do to improve. For example, you noticed most of the visitors will visit your “Features” page but very few of them will actually scroll past even half of the page so many features that you think are important are not actually viewed by the visitors. To improve this, one hypothesis might be using tab or toggle list design to make your page shorter and visitors can select to dig deeper into content that they are interested in by expanding the content. Remember when formulating your hypothesis, change only one variable so that you will know it’s really that variable that is causing the change in conversion.

Now you have your hypothesis, the next is to plan how you are going to measure your results. Defining your success metrics carefully beforehand is important. Otherwise, if there is not enough tracking done during the experiment, it might be hard to draw conclusions and next steps at the end of the experiment.

Experiment - Detail out the experiment setup that you will use to test your hypothesis using Firebase capabilities. Describe the audiences – will all users be able to view the experiment? Or you will only allocate x% of your user base to the experiment? Lay out the details with the rationale behind this decision. Describe the tracking using Firebase Analytics. With your success metrics, what tracking needs to be set up? 

Variations - In this section, describe what variations you would like to test. Layout the design work related and add diagrams, mockups and designs related to the confirmed variation that you’d like to test.

A/B Test Name: Ad Banner Placement (Joe)
User Story Number: ..
Metric (from the HEART grid): User Engagement
Hypothesis: it will affect engagement 

A/B Test Name: Homepage Engagement Optimization (Michael)
User Story Number: US5
Metric: Engagement (specifically Daily Active Users - DAU)
Hypothesis: enhancing the visibility and attractiveness of real-time beach conditions on the app’s homepage, we can improve user engagement, resulting in an increase in daily active users (DAU)
Experiment:
  Audience - All Users, Split 50/50 for each variation
  Duration - 4 Weeks
  Variations - Two versions of Homepage using A/B support in firebase
  Success Metrics - One homepage group should have a higher DAU

A/B Test Name: Wavy Notification Frequency Adjustment (Carlos)
User Story Number:
Metric: Retention
Hypothesis: The hypothesis for this A/B test is that adjusting the frequency of weather alert notifications in the Beach Weather App will impact user retention and churn rate. The problem identified is that users might be overwhelmed by too frequent notifications, leading to app uninstallation, or they might feel underinformed with too few notifications, leading to disengagement. The hypothesis is that finding an optimal notification frequency will balance user engagement and annoyance, thereby reducing churn rate and improving retention.
Experiment: The experiment is designed to evaluate the impact of varying notification frequencies on user engagement and retention. It involves three groups: a control group (Group A) that will receive notifications once per day, a treatment group (Group B) that will receive notifications twice per day, and another treatment group (Group C) that will receive notifications every other day. The experiment will be conducted using Firebase A/B Testing capabilities, with users randomly assigned to one of the three groups in equal proportions. The duration of the experiment is set for 6 weeks to ensure the collection of sufficient data for analysis. To measure the success of the experiment, Firebase Analytics will be used to track key metrics, including the retention rate (the percentage of users who return to the app within 7 days of receiving a notification), the churn rate (the percentage of users who uninstall the app or do not open it for 7 consecutive days after receiving a notification), and notification engagement (the percentage of users who open the app directly from a weather alert notification). These metrics will provide insights into how different notification frequencies affect user behavior and app interaction.
Variations: For treatment groups B and C, the notification frequency will be adjusted as described. The content of the notifications will remain consistent across all groups to ensure that the only variable being tested is the frequency of notifications.


A/B Test Name: Wavy App - Feature Page Design Optimization

User Story Number: 4

Metric (from the HEART grid): Click Through Rate

Hypothesis: 
Problem: The current design of the "Main" page in the Wavy app is causing a high bounce rate, with users not scrolling past the initial section. This suggests that important beach-related features are not being adequately highlighted or accessed by visitors.
Impact: Improving the visibility and accessibility of beach-related features can potentially increase user engagement and adoption of the Wavy app.

Hypothesis: By implementing a tab or toggle list design on the "Features" page of the Wavy app, we can condense the content and allow users to selectively explore beach-related features they are interested in, leading to increased engagement and a higher click-through rate.

Experiment:
Setup: We will allocate 50% of our user base to the experiment group, where they will be exposed to the redesigned "Features" page with the tab or toggle list design. The remaining 50% will serve as the control group and continue to see the original design.
Audiences: Both new and returning users of the Wavy app will be included in the experiment to ensure a representative sample of beachgoers.
Tracking: Firebase Analytics will be utilized to track user interactions with the "Features" page in the Wavy app. Specifically, we will track the number of clicks on individual beach-related features and the overall click-through rate for both the control and experiment groups.

Variations:
Design Variation: 
- The redesigned "Main" page of the Wavy app will feature a tab or toggle list design to highlight beach-related features.
- Mockups and designs specific to the Wavy app will be provided to illustrate the proposed variation.

By systematically testing this single variable change in the context of the Wavy app, created by sophomore college students, we aim to accurately measure the impact of the redesigned "Features" page on the click-through rate of beach-related features, providing valuable insights for further optimization efforts.
