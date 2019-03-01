1.  Explain the differences between `client-side routing` and `server-side routing`.
      - On the Client side of things, routing is handled by javaScript for the initial load. This is different than server side request as those are typically made in Ajax format which will not refresh the whole page, only the updated section. This will cut down on the amount of data that needs to be processed greatly improving speed for both the client and the browser. However, if were dealing with a very large App, the load time can be very slow as the entire site is loaded in the first GET request, and client-side is searching is less optimized.

2.  What does HTTP stand for?
      - HTTP stand for hyper text transfer protocol

3.  What does CRUD stand for?
      - CRUD stands for create, read, update and delete. They are the four basic methods of HTTP      operations.

4.  Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.
      - There are four HTTP methods that can be mapped to the CRUD acronym.
        - GET - retrieving data from a server/database;
        - POST - creating/inserting data into a server/database;
        - PUT - modifying/updating data in a server/database
        - DELETE - remove data from server/databse

5.  Mention three tools we can use to make AJAX requests
      - Three tools available to us to make an AJAX request are
      - Fetch - kicks off a async AJAX request
      - Axios - a promise based HTTP requests;
      - jQuery - a user friendly jS library;
