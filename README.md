# FoodWasteReduction_CV

This project started in November 7th, 2021. Due to a planned change in workspace and in the hopes that I continue this project, I decided to store here for now.

## Journal

### November 7th, 2021

I've been thinking about this project for a while now. A few weeks ago I had to rush over to the Garonzik Auditorium to attend my weekly Eco-Representative meeting. Normally, there are group projects working on different issues on campus such as composting, recycling, 80/20 initiative, etc. I was in the Earth Week committee (Earth week is in April), so we had a lot of time to plan our event. I had a hockey game and a copious amounts of history homework, was very sleep-deprived and zoned out. I started daydremaing about some random things when I overheard the Food Waste committe's conversation. "We tried to measure food waste last year remember? But it was so disgusting and no one wanted to weigh buckets of food in the back fo the kitchen. I think we just simplify our projects and do some cmapagins or whatever." I thoguht I could suggest a solution here with what little knowledge I have of computer vision. What if I could put a camera above the conveyor belt where students put thier plate, so that I can pick up food waste in real time? I went to my dorm after that meeting and came up with an outline that night:

Define the project scope and goals:
The objective is to predict the amount of food waste that will be produced per menu based on historical waste data. This will help in adjusting food preparation quantities and reducing overall food waste at your school.

Collect and prepare data:
Gather historical data on food waste for different menu items, including the menu itself, date, serving size, total servings, and amount of waste produced. You might also want to collect additional features such as day of the week, special events, or weather conditions that could affect food consumption.

Data preprocessing:
Clean and preprocess the collected data. Handle missing or inconsistent values, and convert categorical variables into numerical form using techniques like one-hot encoding or label encoding. Split the dataset into training, validation, and test sets.

Feature engineering:
Perform feature engineering to create new features that might help in predicting the waste per menu. This could include calculating the average waste for each menu item, identifying patterns based on the day of the week or time of the year, or finding correlations between different menu items.

Choose a machine learning model:
Since the problem involves predicting a continuous value, regression models would be appropriate. Select a suitable regression model such as linear regression, decision trees, random forest, or neural networks. You can experiment with different models and choose the one that performs best on your data.

Train the model:
Train the chosen regression model on the preprocessed and feature-engineered training dataset. Adjust model hyperparameters, such as learning rate or tree depth, to optimize the model's performance on your specific task.

Evaluate the model:
Assess your trained model's performance using evaluation metrics like mean squared error (MSE), mean absolute error (MAE), or R-squared (R²). Test the model on the validation and test sets to ensure that it generalizes well to new data.

Optimize and deploy:
If the model's performance is satisfactory, optimize it further for deployment. Deploy the optimized model to a suitable platform, such as a cloud server or an edge device.

Integrate with a planning system:
Develop a planning system that feeds upcoming menu information to the deployed model and receives waste predictions. Use the predictions to adjust food preparation quantities and inform school authorities or cafeteria staff about expected waste levels.

Monitor and improve:
Regularly monitor the system's performance and gather feedback from stakeholders. Continuously update the dataset with new examples and retrain the model to ensure its accuracy and relevance over time.

Share results and raise awareness:
Communicate the results of your project to school authorities, students, and staff. Share insights on food waste patterns and suggest data-driven strategies to minimize waste at your school. Encourage all stakeholders to participate in waste reduction initiatives.
