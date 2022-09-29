# Recipes

Let's enhance a simple, two-page recipe portal that lets you search and view recipes. What if you could rate or comment on the recipe, send a survey, track variations, etc. Also, if you make a change, go ahead and add a new recipe to the app for everyone. Additionally, if you want to know how to build this experience from scratch, check out [CCL1072](https://nowlearning.servicenow.com/lxp?id=learning_course_prev&course_id=000ebf3edb7e0990421266f748961990).

🔔🔔🔔<br>
***CONTRIBUTORS must follow all guidelines in [CONTRIBUTING.md](CONTRIBUTING.md)*** or run the risk of having your Pull Requests labeled as spam.<br>
🔔🔔🔔

## Getting started

1. Fork this repo
2. Go to your ServiceNow instance
3. Go to `System Applications` => `Studio`
4. Once Studio loads, select `Import From Source Control`
5. Use your forked repo to [Import your application](https://developer.servicenow.com/dev.do#!/learn/learning-plans/quebec/new_to_servicenow/app_store_learnv2_devenvironment_quebec_importing_an_application_from_source_control)
6. Make updates to the application
7. In Studio, commit your changes to source control
8. Submit a pull request to the ServiceNowNextExperience/hacktoberfest22-recipes
 `main` branch

### The Recipe DB

Once imported, you can view the experience by going to https://`your_instance_name`.service-now.com/now/recipe-db/

![Recipe DB Example](recipedb.png)

## Participation ideas

Along with new features, or any issues that appear in this repo's issues tab, we welcome you to simply submit a recipe with a picture too!

1. Go to the recipe-db page on your instance (see above)
2. Submit a new recipe with a picture
3. Open the application in App Engine Studio (AES)
4. In the data section, click the preview button on the Recipe row
5. Check the checkbox next to the recipe record you added in the recipe list
6. Right click on the list header and choose "Create Application Files"
7. Choose "New install and upgrades" and select OK
8. Via AES or Studio, commit your changes and open a new Pull Request!
