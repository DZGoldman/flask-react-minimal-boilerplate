Simple boilerplate with for single page flask react app, ready to deploy to heroku.
Built around create-react-app.

## Setup
1. clone repo

    - `git clone https://github.com/DZGoldman/flask-react-minimal-boilerplate`

    - `cd flask-react-minimal-boilerplate`
2. install dependenciess
    - `yarn install`
    - `pip install -r requirements.text`

## Run Development

1. Start flask backend server 
    - `npm run serve`
    - Optional: add env variable `DEV=True` for hot reloading on server

2. (In seperate tab): Start react dev server with hot reloader
    `npm start`

3. Visit http://localhost:3000.

    If you see, "data from the backend received," all is well.

## Deploy To Heroku

1. [Push your project to github](https://github.com/new)  

2. Create new app on heroku.

3. (On heroku) Click "settings" tab
    - add **nodejs** and **python** buildpacks. 
    

4. (on heroku) click "deploy" tab
    - select "Connect on Github" for deployment method. 
    Input repo name

5. Click "Deploy Branch" under "Manual deploy" row.

    Optional: select "Enable Automatic Deploys"

6. Scroll up and click "open app" (at the top right of the page.)

7. Celebrate.


 