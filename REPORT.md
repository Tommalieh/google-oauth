# OAuth Comparative Analysis

## GOOGLE Oauth 

### Research Conducted By: 
1. Muhammed Tommalieh
1. Hammad
3. Darah
4. Yasmin Adaileh

### Overall Score and Comments
#### Score (Out of 10): 10
#### General Comments

It was really informative and mind opening to try and get OAuth from a provider that you know nothing about, through this experience we've expanded on our searching skills, we've learnt how to go through a provider documentation and disect it to be able to get all the information needed to complete the authorization process and get the required user info to get them signing in our app.

### full stack project:
##### Front-end part:
contain the login button xD

#### back-end part:


#### Pros

* Providing a higher lever of security through enabling a provider authorization login, this way the provider will be handling the user and gives us if they should be authorized to our web app.

* Saving lot of time and effort on creating our own authintication modules.

#### Cons

* Lack of ananomity 

* Lack of market saturation; although alot of people use oauth provideres since they're still not used to the process.

### Ratings and Reviews
#### Documentation

* query string parameters for web server applications:
1. `client_id `
2. `redirect_uri`
3. `response_type`
4. `scope`


* **Redirect to Google's**. The response is sent back to our application using the **redirect URL** we specified.

* Google prompts user for **consent** : The user can then consent to **grant access** to one or more scopes requested by our application or refuse the request.
- our application doesn't need to do anything at this stage

* **Handle the OAuth 2.0 server response**.


* **Exchange** authorization code for refresh and access tokens
1. `client_id`  
2. `redirect_uri`
3. `client_secret`
4. `grant_type`
5. `code`

#### Systems Requirements
node.js application 
**dependencies** used:
- `express`
- `superagent`
- `dotenv`
- `jsonwebtoken`

#### Heroku Deployment:
[Heroku](https://class12-googleoauth.herokuapp.com/) 


#### Ramp-Up Projections
4 - 5 Hours

#### Community Support and Adoption levels

How popular is this framework? What big companies are running on it? How is it "seen" in the general JS community?  Is there an active community of developers supporting and growing it?

### Links and Resources
* [framework](https://nodejs.org/en/)
* [docs](https://developers.google.com/identity/protocols/oauth2)

### Code Demos
* [live/running application](https://class12-googleoauth.herokuapp.com/)
* [code repository](https://github.com/401-advanced-javascript-tommalieh/google-oauth)

### Operating Instructions

If someone download our repo, what he/she gonna need do before take to run the application:
* `npm start`
* Endpoint: `/`
  * Returns a pop up window with a consent.
* Endpoint: `/oauth`
  * Returns a JSON object with the user info.
