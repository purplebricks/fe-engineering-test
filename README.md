# Purplebricks FE Engineer Test

 Create a small project that has a property search and a single listing UI using React and Redux, for example on our website you can see the search page, https://www.purplebricks.com/search?query=California and a single listing page https://www.purplebricks.com/detail/homes-for-sale/california/4-bedroom-sutter-yuba-city-95991-zolmz.

We don't expect a polished and fully featured product, a well built simplistic version would be great :)

### The basic things we would look for : 
 
 - Well thought out component structure
 - Clean code that considers best practices like DRY
 - Some unit tests
 - A nice clean looking UI that considers UX
 - Git commit history to show your working
 - A README.md containing instructions of how to run your application locally, explaining code decisions you may have made and what you would have done given more time.

### Bonus points :

- Use CSSModules
- Use Typescript
- Create a Webpack build to bundle all your files
- Consider browser performance - optimise paint times etc
- Consider optimisation around client side caching of requested data from APIs
- Server Side Render your application locally
- Show TDD in your commit history

---

If you'd like to work with dummy data feel free; you are also welcome to use our public APIs here's some info: 

- Search for listings (properties)
	- POST  - https://api.purplebricks.com/listing-search/api/v2/Search
	- Example query - 
	```{"query":"California,USA","page":1,"numberOfBeds":0,"numberOfBaths":0,"maxPrice":700000,"minPrice":50000,"pageSize":12}```
- Fetch a single listing, use it's listingId at this endpoint 
	- https://api.purplebricks.com/listing-details/api/v2/listing/{listingId}
	- example: GET - https://api.purplebricks.com/listing-details/api/v2/listing/zolmz

We expect this to take a couple of evenings. **Please submit your project as a private github, bitbucket or gitlab repository - we will give you the usernames of our reviewers so you can give them access**

## Notes: 

Feel free to use tools like Bootstrap to give yourself a basic layout but keep in mind we do also want to see some of your own SASS/SCSS. We have no problem with you using something like Create React App if you'd like to spend longer on the actual code but we also love to see experience and confidence setting up projects from scratch (webpack, linting etc). If you do decide to use boilerplates include these in your initial commit so we can see your work separate from the boilerplate stuff.
