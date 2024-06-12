# RecipeManagerWPF

RecipeManagerWPF is a Windows Presentation Foundation (WPF) application that allows users to manage recipes, including adding new recipes, viewing existing recipes, and filtering recipes based on specific criteria.

## Features

- Enter new recipes with ingredients and steps.
- View all recipes sorted by name.
- Filter recipes by ingredient, food group, or maximum calories.
- User-friendly graphical user interface.


## Getting Started

Follow these steps to compile and run the RecipeManagerWPF application.

### Step 1: Clone the Repository

Clone the repository from GitHub (or download the project files if you are not using a version control system).

```bash
git clone https://github.com/ST10357602/PoE/RecipeManagerWPF.git
cd RecipeManagerWPF

###Step 2: Open the Project in Visual Studio
Open Visual Studio 2022.
Click on File > Open > Project/Solution.
Navigate to the RecipeManagerWPF directory and select the RecipeManagerWPF.sln file.

Step 3: Restore NuGet Packages
Visual Studio should automatically restore any necessary NuGet packages. If not, you can restore them manually:

Step 4: Build the Solution
Go to Build > Build Solution or press Ctrl + Shift + B.
Ensure there are no build errors. If there are errors, check the Error List and resolve them as needed.
Step 5: Run the Application
Press F5 or click the Start button in Visual Studio.
The application should open, and you can start using the RecipeManagerWPF application.
Usage
Adding a New Recipe
Click on the "Enter a New Recipe" button.
Fill in the recipe details, including ingredients and steps.
Click "Save Recipe" to save the new recipe.
Viewing All Recipes
Click on the "View All Recipes" button.
A list of all recipes will be displayed.
Select a recipe to view its details.
Filtering Recipes
Enter criteria in the filter text boxes for ingredient name, food group, or maximum calories.
Click on the "Apply Filters" button.
The list of recipes will be filtered based on the entered criteria.
Project Structure
RecipeManagerWPF.sln: The solution file.
MainWindow.xaml: The main window XAML file containing the UI layout.
MainWindow.xaml.cs: The code-behind file for MainWindow.xaml.
EnterRecipeWindow.xaml: The window for entering new recipes.
EnterRecipeWindow.xaml.cs: The code-behind file for EnterRecipeWindow.xaml.
EnterIngredientWindow.xaml: The window for entering new ingredients.
EnterIngredientWindow.xaml.cs: The code-behind file for EnterIngredientWindow.xaml.
EnterStepWindow.xaml: The window for entering new steps.
EnterStepWindow.xaml.cs: The code-behind file for EnterStepWindow.xaml.
Recipe.cs: The model class for a recipe.
Ingredient.cs: The model class for an ingredient.
RecipeStep.cs: The model class for a recipe step.
RecipeManager.cs: The class containing logic for managing recipes.
Troubleshooting
If you encounter any issues, check the following:

Ensure all necessary namespaces are included at the top of each C# file.
Verify that all class names are correctly referenced.
Check the Error List in Visual Studio for specific errors and their resolutions.
Ensure that the correct version of .NET SDK is installed.
