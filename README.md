# Developer Test: Node.js

The objective to this application is to demonstrate your capabilities as a nodejs application developer. To keep the problem space small, we'll build a small application that is geared towards storing movies. 

A basic project template has been created in this repository, feel free to download it, and utilize it.  Howerver, it's not necessary to do so.


## Requirements

1. The application will allow a user to query, add, remove, update and view a movie. 
2. The application will also allow a user to query, add, remove, update, and view actors, and directors.
3. The application should expose a restful service, and either curl or postman should be used to validate that REST apis.
4. The data should be persisted in mongo database.
5. The application should use express.js for the api layer (already installed as a dependency)
6. (Optional) *Brownie Points for allowing a user to associate directors, actors, and movies.* 
7. (Optional) *Brownie Points for deploying it somewhere like heroku, or somewhere where we can play around with the application*

## Persistence and Models

> The application should store the following information in a mongo database. The storage of these models are open to interpretation, meaning, you may use a collection based approach, versus and embedded, but be prepared to discuss the decision on why you used the strategy you did. 
> 
> The models may be optimized as needed, as long as the following information is stored below.

### Movie
 * Name (String)
 * Description (String) [optional]
 * Year Released (Number) [range: 1800 - present year]
 * Rating (Number) [range: 1-10]
 * Actors (Array<Actor>) [default: []]
 * Directors (Array<Director>) [default: []]

### Actor
 * Name (String)
 * Age (Integer) [range: 0-125]
 * Gender (M/F) [default: 'M']
 * Agent/Agency (String|Actor|Director) [optional]
 * Movies Acted In (Array<Movie>) [default: []]

### Director
 * Name (String)
 * Age (Number) [range: 0-125]
 * Gender (M/F) [default: 'M']
 * Movies Directed (Array<Movie>) [default: []]


## Testing

Testing is a big part of our culture. We strive to have decent code coverage and tests that are meaningful. Write any necessary tests.  Mocha and Chai are installed as developer dependencies by default, but you may use any library you deem necessary.

# Summary

Zip up the source code, and send it to: <ganapathi.adapa@berkadia.com>

--- 

**Answer the following questions in the body of the e-mail:**
> 1. What went well?
> 2. What would you have done differently?
> 3. What are you passionate about?
> 4. (Optional) Show off your favorite project you contribute to.  Bonus points for the github repository.

---

Thank you for your time and letting us get to know you via code. We look forward to meeting you.

If you have any questions, or comments, please feel free to email: <ganapathi.adapa@berkadia.com>

