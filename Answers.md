- Explain the differences between `client-side routing` and `server-side routing`.

Client-side routing loads all necessary resources for a website on initial load, and then routes the user based on resources that have already been retrieved. This means we don't need to wait for a response from a server or a refresh on each page change. Server-side routing sends requests to a server for each individual page, and therefore loads quicker initially, but is slower when being routed between pages.

- Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.

HTTP GET - SELECT/Request
HTTP PUT - UPDATE
HTTP POST - INSERT/Create
HTTP PATCH - When PUTting a complete resource representation is cumbersome and utilizes more bandwidth
HTTP DELETE - DELETE

- Mention three tools we can use to make AJAX requests.
  Axios, Jquery,
  and Fetch
