Food Recipe and Nutrition guide.(Tracks calorie intake?)
Includes most popular recipes

Flow:

Use webservices api from food apis.

Java classes:(add versioning on implementations) check if latest version. ask to update if not (optional)


UserService(tracks the current version,user type, )
UserServiceImpl// should have factory of other services



CheckNutrionService - methods:
					- getAllFood
					- getByFood(Return FoodInfo)
					// Create update delete (For admin only)

CheckNutritionServiceImplV1

CheckRecipeService
CheckRecipeServiceImplV1

PersonalRecipeService
PersonalRecipeServiceImpl


Back end classes

FoodInfoDAO
FoodInfoDAOImpl

FoodRecipeDao
FoodRecipeDaoImpl

Controller classes

Objs:

FoodInfo,
FoodRecipe extends FoodInfo


Back end:

Postgres db?

Tables:

FoodInfo
RecipeAndIngredients
Ingredients
PersonalRecipe
User

 