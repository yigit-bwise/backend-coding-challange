## ⚡️ Buddywise - Backend Coding Challange

In this challange you are asked to design and implement a simple API to extract and deliver information from a given static data file found in the `resources` folder. The solution must be implemented in `Python` and preferably use `Flask` or `FastAPI` framework.

Please downlaod the resources folder and create a new repo (make sure its private and add `yigit-bwise` as a contributer to it once you are ready to share) and send a link to `yigit@buddywise.co`. For any questions you can reach out to the same email address.

Best of luck 🍀


## 🎯 API Requirements
Your API must provide the following:

- Given a company, the API needs to return all their employees. 
- Given 2 people, provide their information (Name, Age, Address, phone) and the list of their friends in common which have brown eyes and are still alive.
- Given 1 person, provide a list of fruits and vegetables they like. This endpoint must respect the following format for the output: `{"name": "Bond Stokes", "age": "30", "company": "Zolarity", "fruits": ["banana", "strawberry"], "vegetables": ["beetroot", "cucumber"]}` Note that data is providing only the "favorite food" per user, and you need to transform the data to display fruits and vegetables seperately.

- Endpoints you have defined and how to interact with them are documented in the repo
- Data used by the API is pushed and eventually fetched from a DB service of your choice (please articulate the reasoning behind your choice)
- Tests are included. (It's up to you what to test and how to test them. We are at least looking for some basic unit tests to give this one a pass)
- API is dockerised and can be run via docker-compose locally (docker-compose file should be included in the repo)

📝 Please include a `Solution.MD` file in the main directory, add just a few of senteces around the choices you made and anything else you think is worth highlighting on your solution.
