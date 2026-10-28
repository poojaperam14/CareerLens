# CareerLens — AI-Powered Career Exploration

CareerLens is a Python-based career exploration tool that helps users
discover job matches based on their skills and explore job-market insights.

## Features

- Skill-based job recommendations
- Identification of matching and missing skills
- Job posting insights by job title
- Salary comparisons across job categories
- Work-mode distribution analysis
- Interactive web dashboard built with Gradio

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Gradio
- Google Colab

## How It Works

1. Loads and explores a job-posting dataset.
2. Analyzes job roles, skills, salaries, and work modes.
3. Compares user skills with the skills listed for each job.
4. Ranks job titles using skill overlap.
5. Displays career insights in an interactive dashboard.

## Machine Learning

A Random Forest regression model was tested for salary prediction.
Its performance did not beat a simple average-salary baseline.
Therefore, its predictions should not be treated as reliable salary estimates.

## Dataset Limitations

- Salary patterns may not reflect the real job market.
- Recommendations depend on skills listed in the dataset.
- Skill-match percentages do not measure the chance of getting hired.
- Results should be used for learning and exploration only.

## Run the Project

1. Open the CareerLens notebook in Google Colab.
2. Run the notebook cells in order.
3. Run the Gradio app cell to launch the dashboard.
4. Open the generated public URL to use the app.

## Future Improvements

- Use verified job-market and salary data.
- Improve job matching and recommendation methods.
- Add career learning roadmaps.
- Deploy the app on a hosting platform.

## Author

Developed as a portfolio project to explore Python, data analysis,
machine learning evaluation, and interactive application development.
