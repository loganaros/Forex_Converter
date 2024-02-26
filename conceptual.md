### Conceptual Exercise

Answer the following questions below:
  
- What are important differences between Python and JavaScript?
  Python is an object oriented programming language, and programs can be ran independently of being in a browser.  JavaScript is also object oriented, but can be used for both front and back end development
- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing.
  You can use 'dictionary.get(value)' to get or return none, or wrap the expression in an exception catching block.
- What is a unit test?
  A unit test is testing a specific part of an application, such as one function.  
- What is an integration test?  
  An integration test is testing all of the parts of an application together to make sure they all work together as expected
- What is the role of web application framework, like Flask?
  A web application framework makes running a web server much easier by handling a lot of the tasks and providing easy to use functions and methods.
- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?
  A query string is good for simple data that may modify the content within a page, such as a search term or sorting value. A route URL is more useful in being a container/path for your webpage.
- How do you collect data from a URL placeholder parameter using Flask?
  You create a URL variable using app.route('/example/`<variable>`')
- How do you collect data from the query string using Flask?
  After importing request from Flask, you use request.args['value']
- How do you collect data from the body of the request using Flask?
  You use the 'request' object
- What is a cookie and what kinds of things are they commonly used for?
  Cookies store temporary data within the browser for websites and are commonly used to store information specific to the user or session.
- What is the session object in Flask?
  The session object is an object that stores itself as a cookie and can be used as a dictionary to store multiple variables/information.
- What does Flask's `jsonify()` do?
  jsonify() converts data into true JSON file format.