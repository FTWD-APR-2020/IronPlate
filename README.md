# IronPlate

# Start server
## cd backend/
## npm i 
## nodemon 


# Start client
cd frontend/ 
npm i 
npm start


# Deploy DB
sign in with Atlas. 
Get connection string and add it to .env file.   

# Deploy to Heroku
heroku create 
git add . 
git commit -m 'deploying' 
git push
git push heroku master
add convig var for MONGDB_URI in heroku dashboard


# Deploy to Netlify
Login to Netlify & Select the repo
In backend/app.js add client url generated by Netlify

