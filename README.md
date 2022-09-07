# CMPG-323-Project-2---30857465
api project

# how it works
1.Select an API. First things first, you'll want to find an API you could incorporate into your business. ...
2.Get an API key. ...
3.Review the API documentation. ...
4.Write a request to an endpoint. ...
5.Connect your app.

swagger:
1.user will have to create a user
2.user will then login
3.user will recieve a jwtToken
4.enter the the token with "bearer (jwttoken)"
5.user will then have access to api endpoints 

# List of endpoint 
[HttpPost] - [Route("login")]
[HttpPost] - [Route("register")]
[HttpPost] - [Route("register-admin")]

// GET: api/Categories -- getall categories
// GET: api/Categories/5 -- find
// PUT: api/Categories/5 -- update
// POST: api/Categories -- create category
// DELETE: api/Categories/5 -- delete
private method in the API that checks if a Category exists (based on the ID parsed through) before editing or deleting an item

// GET: api/Devices -- get all devices
// GET: api/Devices/5 -- find device
// PUT: api/Devices/5 -- update device 
// POST: api/Devices -- create device
// DELETE: api/Devices/5 -- delete
private method in the API that checks if a Device exists (based on the ID parsed through) before editing or deleting an item

// GET: api/Zones -- get all zone
// GET: api/Zones/5 -- find zone
// PUT: api/Zones/5 -- update zone
// POST: api/Zones -- create zone
// DELETE: api/Zones/5 -- delete zone
private method in the API that checks if a Zone exists (based on the ID parsed through) before editing or deleting an item

