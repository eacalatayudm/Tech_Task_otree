# Tech_Task_otree
otree - Variation of the Trust game with randomization and sliders.

## Task 1: Development
### Backend:
  - Randomization for groups was done.
  - Randomization for roles was done.
  - The optional bonus of making both randomization features session configurable was also done.
  ![screenshottask1](https://user-images.githubusercontent.com/119822097/205536675-fbb9ab82-c8a6-45aa-b554-0f82190fa1c2.png)
  
### Frontend:
  - The display of results in a table per round was done.
  - The implementation of the slider for choosing the amount sent from Player A was done.
  - The implementation of the slider for choosing the amount sent back from Player B was partially done, was not able to find a way to set the upper limit of the slider to the variable of 3 times the amount sent from Player A in turn 1.

## Task 2: Deployment
  - Postgres and psycopg2 were installed using 'pip install --'
  - PostregSQL was installed locally on Windowsx64.
  - The environment variable DATABASE_URL was set to 'postgres://postgres@localhost/django_db' as the otree documentation mentions: https://otree.readthedocs.io/en/master/server/server-windows.html
  - The command otree resetdb was used from the terminal with no issues validating the deployment of the database.
  ![screenshottask2](https://user-images.githubusercontent.com/119822097/205536791-43cbd910-fd11-4c06-a4b9-728381f82669.png)
  - The database can be visualized properly, locally exceuted using DB Browser for SQLite:
  ![screenshottask2randomsession](https://user-images.githubusercontent.com/119822097/205537221-62e98996-51b9-4d6f-8d30-df2b73020c31.png)
  - Session was launched succesfully in production mode:
  
  ![screenshottask2prodmode](https://user-images.githubusercontent.com/119822097/205537472-8e701ea1-2cae-49df-b694-134eb8b283b9.png)
