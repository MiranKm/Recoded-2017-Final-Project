# News App
Create a news application using the guardian API and store the response in SQLite

- Contains a main activity which shows either a ListView of sections or a ViewPAger with Tabs of the sections, and when a section is selected, the section’s news is loaded into a ListView in another Activity or Fragment.
- The ListView should contain at least the article’s title, image, date.
- A details activity which will show all the details of an article, including the article’s body, date, and author.
- A settings activity in which the user can hide sections from the home screen.
- When caching, the new results should overwrite the old ones (the database shouldn’t keep holding into the old data when caching new ones).
- The application’s UI should be multilingual (supports at least 2 languages).
- Clean UI is required.
- The app will be submitted using GitHub.
- You can use any external library you want.
