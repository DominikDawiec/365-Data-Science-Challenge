# 365 Data Science Challenge

This repository contains the code and data documentation for the 365 Data Science Challenge, where I have analyzed student engagement on a data science course site. The project includes data cleaning, data visualization, and model building. The data files can be found in the [data_files](data_files) directory and the code in the [notebook.ipynb](notebook.ipynb) file.

#### Project Status: [Completed]

## Application Link
To access the application, please click on this link: [Sushi Roll App](https://sushiroll.streamlit.app/)

## Workflow
To understand the workflow of the Sushi Roll App, please refer to the included [workflow](workflow/workflow.pdf).

## Additional Features
In addition to the core functionality of the app, I've added a few additional features to enhance the user experience:

### User-Generated Recipes
I've created a Google Sheets-based database that allows users to add their own sushi roll recipes to the app. The connection to the database is automatically refreshed every 10 minutes, so users can see the latest additions to the database.

### Ingredient and Roll Images
To make the app more visually appealing, I've added images for each ingredient and sushi roll. These images were created using Dalle-2, a state-of-the-art language model for image generation. If an ingredient does not have an image with the same name as the ingredient, a default "nopic.png" image with a question mark is shown.

### Interesting Text and Fun Fact
While the app is loading sushi rolls, the user is presented with interesting text about sushi and sushi rolls to make the waiting time more engaging. At the end of the suggestions, a random fun fact about sushi is presented for the user's enjoyment.

## How to Use
1. Clone this repo to your local machine.
2. Install the necessary libraries by running pip install -r requirements.txt in your command line.
3. Run the application by running streamlit run app.py in your command line.
4. Choose your desired ingredients from menu.
5. Click on the "Make Sushi" button to receive a list of possible sushi rolls based on your selected ingredients.

## Contact
* Please feel free to reach me through my [LinkedIn](http://linkedin.com/in/dominikdawiec/).  
