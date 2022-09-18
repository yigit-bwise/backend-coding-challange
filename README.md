## ⚡️ Buddywise - Backend Coding Challange

In this challange we would like you to design and implement a simple API to extract and deliver information from a given static data file found in the `resources` folder. The solution must be implenented in `Python` and preferably use `Flask` framework, although this one is not required.

Please fork this repo and send your solution repo link to yigit@buddywise.co. For any questions you can reach out to the same email address.


## 🎯 API Requirements
Your API must provide the following:

- Given a company, the API needs to return all their employees. 
- Given 2 people, provide their information (Name, Age, Address, phone) and the list of their friends in common which have brown eyes and are still alive.
- Given 1 person, provide a list of fruits and vegetables they like. This endpoint must respect the following format for the output: `{"name": "Bond Stokes", "age": "30", "company": "Zolarity", "fruits": ["banana", "strawberry"], "vegetables": ["beetroot", "cucumber"]}` Note that data is providing only the "favorite food" per user, and you need to transform the data to display fruits and vegetables seperately.

- Endpoints you have defined and how to interact with them are documented in the repo (no fancy documentation format/tool is required, as long as its clear for the reader, anything goes)
- Tests are included. (It's up to you what to test and how to test them. We are at least looking for some basic unit tests to give this one a pass)

## ☑️ Checklist

Fulfilling the requirements listed above for the API is enough to submit your solution. However, we would like you to go the extra mile and check as many additional boxes listed below as possible. It is up to you how much time you would like to invest into this solution. You can check one of them or all of them, there is no order (there might be dependencies tho) for which ones you want to complete.

- [ ] API is dockerised and can be run via docker-compose locally (docker-compose file should be included in the repo)
- [ ] Data used by the API is pushed and eventually fetched from an AWS DB service of your choice (please articulate the reasoning behind your choice)
- [ ] API is hosted on an EC2 instance and can be queried publicly given the IP address of the machine
- [ ] API is auto-scaled via AWS application load balancer and can create new instances to match the demand when there is high volumes of traffic coming in. (It is up to you how to configure the scale conditions, anything that is working would get a pass on this part. Please briefly describe the configuration and articulate why you chose to do so.)

📝 Please include a `solution.txt` file in the main directory, add just a few of senteces around the choices you made and anyhting else you think is worth highlighting on your solution. Try to keep this document short.
