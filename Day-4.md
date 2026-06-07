---
---

--- Before Day-4 ---
I already knew same as before
--- 

## Day-4 Checklist

- [ ] I know the 5 core HTTP methods (GET, POST, PUT, PATCH, DELETE) and what each is used for
- [ ] I can read a status code and know what went wrong — e.g., 401 vs. 403 vs. 404 vs. 500
- [ ] I can open Chrome DevTools Network tab, find a request, and inspect its headers, payload, and response
- [ ] I can copy a browser request as a cURL command and run it in the terminal
- [ ] I can change the `User-Agent` in the browser and see the change in the Network tab
- [ ] I can use `curl` to make a GET request with query parameters and a POST request with a JSON body
- [ ] I have a running FastAPI app with at least two endpoints (`GET /health` and `POST /echo`)
- [ ] I can test my API using the Swagger UI at `/docs` and via `curl` from the terminal

--- After Day-4 ---
I learned these things .. HTTP methods...
1)GET — “Read data”.Fetches data from a server.Only retrieves data
2)POST — “Create new data”.Sends data to create something new on the server.
3)PUT — “Replace full data”.Replaces the whole resource
4)PATCH — “Update part of data”.Updates only specific fields.Partial update.
5)DELETE — “Remove data”.Deletes a resource from the server.
6)An API (Application Programming Interface) is just a way for two systems to talk to each other. API tools give you a user-friendly interface to do that visually.
without coding Send API requests (GET, POST, PUT, DELETE).
Popular no-code API tools=> Postman,Insomnia.API gives DATA, not a webpage.
7)HTTP status codes tell you what happened when you made an API request. 401 — Unauthorized(login is invalid/Wrong API key)
403 — Forbidden(“I know who you are, but you’re not allowed”), 404 — Not Found(“The resource doesn’t exist”/“I can’t find what you asked for.”), 
500 — Internal Server Error(“I tried, but my code crashed.”)
8)GET request with query parameters-->curl "https://httpbin.org/get?name=john&age=25"
9)POST (send data)-->curl -X POST https://httpbin.org/post

---

--- Feedback (Suggestions for the TDS Team) ---
This is my feedback ...
---

---
---
