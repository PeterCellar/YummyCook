# YummyCook

Mobile application created with .NET MAUI technology.

Application has been made as an university project at FIT VUT by me and another two colleagues.

---

## Supported OS
	
	- Android
	- IOS

---

## Data

### Firebase Recipe Model
	
	- Name
	- Description
	- Rating
	- Preparation time
	- Type
	- Cuisine 
	- Ingredients
	- Steps
	- Tools
	- Use diets
	- Allergens
	- Photo
	- Public

### Recipe Model
	
	- Name 
	- Description
	- RecipeProcedure
	- Rating
	- CookingTime
	- FoodType
	- CuisineType
	- KitchenAppliances
	- Diets
	- Allergens
	- SelectedIngredients
	- Pictures
	- Favorite

### Profil
	
	- Name
	- Image
	- Diets
	- Alergy
	- Tools
	- Language

### Kitchen
	
	- Kitchen

### Ingredient
	
	- Name 
	- Category
	- Fat
	- Sugar
	- Proteins
	- Calories
	- Have
	- Buy
	- InCart
	- ToBuy
	- InNewRecipe

---

## Funcionality

Application downloads json data from Firebase database and displays them to user.

User can browse various recipes, pick favorite ones and create new, create his own shopping list, select a theme color or change 
application language.  

### Recipe

Get existing recipe or create new one. Filter recipes by name, preparation time or other filters. 

Pick your favorite recipe or calculate nutritional values.

### Ingredient

Mark ingredients you already have in the kitchen. Add missing ingredients to a shopping list or remove bought ones.

### Profile

Add your personal diets, allergies, kitchen tools or update steps in your recipe. 

Set your profile picture or pick your favorite theme color.

---

## Debugging
- Emulator or physical device
- USB or Wi-Fi

### Activation of wireless debugging
Settings -> developer options (must be activated: Software information -> 7x click on serial number) -> Tuning
- wireless tuning: (mobile) Android >= 11, (VS) Android SDK >= 30
	- open up Android Adb Command Prompt in Visual Studio
```bash
adb pair [IP:port (Data in a mobile)] 

Enter pairing code: 

adb connect [Mobile IP]
```