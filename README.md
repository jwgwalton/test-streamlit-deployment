# Setup

## Deploying to Heroku
I'm using Heroku so i can add CI/CD to this project. 
I initially looked at Streamlit community cloud but from what i could see it was only manual deployments

-   Sign up to Heroku & create an API key.
-   Add the API key to the repository secrets as `HEROKU_API_KEY`
    - Open the settings tab & select secrets & variables -> Actions -> Repository secrets