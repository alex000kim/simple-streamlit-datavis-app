# simple-streamlit-datavis-app

## Prerequisites

- Pipenv

## Install dependencies

```bash
pipenv shell
pipenv install
```



## Run the app locally

```bash
streamlit run app.py
# the app will be accessiable at http://localhost:8501/
```

## Deploy the app to heroku

1. Create account in heroku.com
2. Install Heroku CLI: https://devcenter.heroku.com/articles/heroku-cli#download-and-install
3. Create new app and give it a name

![create_new_app_1.png](heroku_deploy_images\create_new_app_1.png?raw=true)

![create_new_app_2.png](heroku_deploy_images\create_new_app_2.png?raw=true)

4. Add `heroku` repository: 

   ``` bash
   heroku git:remote -a <MY_HEROKU_APP>
   ```

![add_heroku_repo.png](heroku_deploy_images\add_heroku_repo.png?raw=true)

5. Deploy to Heroku

```bash
git push heroku HEAD:master
```

![deploy_to_heroku.png](heroku_deploy_images\deploy_to_heroku.png?raw=true)

The app will be accessible at https://<MY_HEROKU_APP>.herokuapp.com/ 

e.g. https://my-first-streamlit-app.herokuapp.com/

