# food-db
JSON food database personal project

Not entirely sure how this is going to work, but I'll try to smush in all my ideas here

Command	Description	Admin-only?	Bot Section

/add_recipe	Add a recipe with title, ingredients, steps, cooking time, tags, and country/cuisine.	Y	Recipe Management
/get_recipe [name or ID]	Get detailed information about a specific recipe.	N	Recipe Management
/list_recipes [filters]	 List recipes optionally filtered by tag, ingredient, cuisine, or cooking time.	N	Recipe Management
/delete_recipe [ID]	Delete a recipe.	Y	Recipe Management
/search_recipes	Query by ingredient, tag, cooking time, or country/cuisine.	N	Recipe Management
/add_ingredient	Add a new ingredient with name, type, origin, description.	Y	Ingredient Database
/get_ingredient [name]	View details on a specific ingredient.	N	Ingredient Database
/list_ingredients [type]	List ingredients by type, origin.	N	Ingredient Database
/cook [ingredient1, ingredient2, ...]	Finds recipes that match or nearly match the given list of ingredients. Include the closest recipe if no exact matches (highest %ingredients matched).	N	Ingredient Database
/substitute [ingredient]	Suggest substitutes for a specific ingredient.	N	Ingredient Database

Food Categories								
Soups & Stews	Handhelds	Salads	Dry noodle	Wet noodle	Rice & Grain-Based Dishes	Meat & Protein-Centric	Seafood	Casseroles & Bakes
* Soup	* Sandwich	* Green Salad						
* Stew	* Wrap	* Pasta Salad						
* Broth	* Taco	* Grain Salad (e.g., quinoa, couscous)						
* Chowder	* Burrito	* Bean Salad						
* Bisque	* Quesadilla	* Fruit Salad						
* Chili	* Burger	* Slaw						
	* Hot Dog							