# UNICEF-Challenge
My project for the Grow Ethereum Hackathon - The UNICEF Challenge: Reducing The Digital Divide

## Epic:
In this MVP scenario schools, as "makers", can use distributed consensus blockchain technology to "make" an order to fund ISP connectivity. Governments and others, known as "takers", can take the order to fulfill the order request.  

### Stories
In this MVP, Users can:
- see a list of countries
- select a specific country and view the schools related to the selected item
- view the schools that are connected and not connected for that country
- see the status of that country (e.g. if donors have provided funding, if ISPs are engaged, number of schools connected and not connected etc.)

### Sprints
- [x] days 0-1: draft epic, user stories, and sprint timeline
- [ ] days 1-5: create local instance of magic-box front-end, back-end, and pull school connectivity data from api
- [ ] days 6-10: integrate web3 user capability for distributed order making and taking
- [ ] days 11-15: polish front end design

### Tech Stack
- MongoDB to process API data
- ReactJS / OpenStreet Map for front-end
- For order making and taking, an early candidate is 0x integration, for sotring transactions on the Ethereum blockchain.
