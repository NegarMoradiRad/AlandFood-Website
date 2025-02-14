About Website:
In this project, I designed a website whose frontend is Plasmic and its backend is n8n and its database is Google Sheets.
In the past, I created a Telegram bot in n8n that provided food recipes. Here, I created a website called AlandFood! This website has the following features:
##Home Page:
```bash
I have stored the names of a number of foods and other information about them in my database.
A list of these foods can be seen on the home page. This list includes the name of the food, a photo, and the ingredients of that food.
'''
'''bash
This home page also has a searchbar that allows you to search for the name of the food and find it faster.
Each food page
The user enters the relevant page by clicking on each food. This page displays the food photo, title, and ingredients, and also includes the following sections:
'''
'''bash
– Food inventory count\n
– Average cooking time\n
– A button to register a food order\n
'''
When the user clicks on the order, a form is displayed for him where the user must register his address and name.
At the end of the form, when the user clicks on the confirm button, their order is saved in the database and one unit is also deducted from the inventory of that food (the database stores the user's order date, user name, type of food, and address.)
Notify the chef
Allandfood currently has a chef whose number is the same as my mobile number! When someone places an order, they will be notified via SMS to my Telegram number!
Also, to make it more attractive, I decided to add an artificial intelligence section to my site, so I added a button to the food page called Get Recipes from Artificial Intelligence! Users can view the recipe for that dish by clicking on it.

This is a Next.js project bootstrapped with [`create-plasmic-app`](https://www.npmjs.com/package/create-plasmic-app).

## Getting Started

First, run the development server:

```bash
npm run dev
```

Open your browser to see the result.

You can start editing your project in Plasmic Studio. The page auto-updates as you edit the project.

## Learn More

With Plasmic, you can enable non-developers on your team to publish pages and content into your website or app.

To learn more about Plasmic, take a look at the following resources:

- [Plasmic Website](https://www.plasmic.app/)
- [Plasmic Documentation](https://docs.plasmic.app/learn/)
- [Plasmic Community Forum](https://forum.plasmic.app/)

You can check out [the Plasmic GitHub repository](https://github.com/plasmicapp/plasmic) - your feedback and contributions are welcome!
