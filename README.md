# datfun-07-ml

This project will employ simple linear regression - a type of supervised learning under machine learning (ML) - to train a model and use the resulting module to make predictions. 

Steps already completed:
1. [Set up the Machine](https://github.com/denisecase/pro-analytics-01/blob/main/01-machine-setup/MACHINE-SETUP.md)
2. [Initialized a new Project](https://github.com/denisecase/pro-analytics-01/blob/main/02-project-initialization/PROJECT-INITIALIZATION.md)

## Before/During Working on the Project
1. Pull the Latest Changes from GitHub 
   
```shell
git pull origin main
```

2. Activate the Project Virtual Environment

```powershell
source .venv/bin/activate
```

3. Install Dependencies As Needed 

```powershell
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

4. Run Script 

```powershell
source .venv/bin/activate
python3 demo-script.py
```

## Git add-commit-push command 
```shell
git add .
git commit -m "custom message"
git push -u origin main
```

## Steps to Perform
### Start a New Jupyter Notebook
- Open your project repository folder in VS Code. 
- Open a terminal in your root project folder and run git pull to make sure you have the latest changes from GitHub. (It's good practice to ALWAYS pull before starting work.)
- Start a New Notebook
- Create a new notebook in your repository named yourname_ml.ipynb.
- In a Markdown cell at the top of the notebook, add:
  - The Notebook Title
  - Your Name as Author
  - A Clickable Link to your GitHub project repository.
- In a Python cell just after, add all your import statements, organized following standard conventions. 

### Chart a Straight Line (Part 1)
- Add a Markdown cell with a second-level heading named Part 1 - Chart a Straight Line
- Follow the instructions from 10.16 (starting page 414).
- Use Markdown cells to create section headings as you work. 
- Use pandas DataFrames to plot Celsius vs Fahrenheit 
- Refresh your understanding of the equation for a line (y = mx + b) and be familiar with the use of:
  - m = the slope of the line (rise over run or delta y over delta x)
  - b = the y-intercept of the line (where the straight line crosses the y axis). 
- Run the whole notebook to verify. Fix any issues or warnings.
- Git add / commit / push your changes to GitHub. 

### Predict Average High Temperature in NYC in January (Part 2)
Use Linear Regression on Average High Temperatures in NYC in January 
- Add to your notebook as you work through the process. Add a Markdown cell with a second-level heading named Part 2 - Prediction. Use third-level Markdown headings for each section listed below. Copy and paste the section heading, and add a ### space before each. 
  - Section 1 - Data Acquisition
    - Follow the instructions to load NY City January high temperature from a csv file into a DataFrame.
    - Rather than nyc, name the dataframe nyc_df to reinforce the DataFrame operations.
    - Add all imports to the top of your file, just under the Markdown Introduction. Follow conventions. 
  - Section 2 - Data Inspection
    - Follow the instructions to view head and tail of the file. 
  - Section 3 - Data Cleaning
    - Follow the instructions to clean the data. Improve the column names and clean up the date series. 
  - Section 4 - Descriptive Statistics
    - Set the display precision to 2 decimal places. Use 'display.precision' instead of 'precision' as shown in the text.
    - Use describe() to calculate basic descriptive statistics for the dataset. 
  - Section 5 - Build the Model
    - Use the SciPy stats module linregress function to calculate slope and intercept for the best fit line through the data.
  - Section 6 - Predict
    - Use your model to predict the "average high temp in Jan" for the year 2024 (just like they did for 2019).
  - Section 7 - Visualizations
    - Follow the instructions and use Seaborn to generate a scatter plot with a best fit line.
    - Set the axes and the y scale as directed
    - Customize your chart and notebook as you like to make your work clear and compelling. 

### Predict Average High Temperature in NYC in January (Part 3)
Use Linear Regression on Average High Temperatures in NYC in January using a different approach.
- Continue the project by following the steps in 15.4 (staring page 620 in your textbook). 
- This time, we'll use scikit-learn estimator, and we'll practice splitting data for training (to build a model) and testing (testing our model against known values). 
- Follow the instructions all the way though charting it again with the specified axes.
- These sections are new - add these numbered sections to Part 3. Use third-level Markdown headings for each section listed below. Copy and paste the section heading, and add a ### space before each.
  - Section 1 - Build the Model
    - Use test_train_split to split the data into parts for training and testing.
    - Check the shape of each data set.
    - Train the model using Linear Regression Fit. 
    - View the returned coef_ and intercept_  attributes need for the line equation (y = mx + b)
  - Section 2 - Test the Model
    - Test the model as directed.
  - Section 3 - Predict 
    - Use your model to predict the "average high temp in Jan" for the year 2024 (like they did for 2019).
  - Section 4 - Visualizations
    - Follow the instructions and use Seaborn to generate a scatter plot with a best fit line.
    - Set the axes and the y scale as directed
    - Customize your chart and notebook as you like to make your work clear and compelling. 
Run the whole notebook to verify. Fix any issues or warnings.
Git add / commit / push your changes to GitHub. 

### Add Insights (Part 4)
- At the end of the notebook, add a second-level Markdown Heading for Part 4 with some remarks comparing the two methods.
- Excellent analytical skills need professional communication skills to be of maximum benefit. 
- Your narrative and the way you present your work is key. 

