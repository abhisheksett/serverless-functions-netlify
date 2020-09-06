# Serverless Functions

This is the source code for a Frontend Masters course about serverless functions.

## Resources

- [Netlify Functions](https://www.netlify.com/products/functions/?utm_source=fem-sls&utm_medium=functions-jl&utm_campaign=devex)
- [Netlify Identity](https://docs.netlify.com/visitor-access/identity/?utm_source=fem-sls&utm_medium=functions-jl&utm_campaign=devex)
- [Hasura](https://cloud.hasura.io/)
- [Heroku](https://www.heroku.com/)
- [OMDB Identity](http://www.omdbapi.com/)


### Variables

Following are the variables need to be added in .env file:

` OMDB_API_KEY`
` HASURA_API_URL`
` HASURA_ADMIN_SECRET`

### Script

- To start the application: `netlify dev`


### Hosting

The site is hosted at: https://sett-serverless.netlify.app/ 


### Identity used

- Netlify Identity
- Login is done with [netlify-identity-widhet](https://github.com/netlify/netlify-identity-widget)