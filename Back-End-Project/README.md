## Spongebob's Recipe Book
### Overview
Spongebob's recipe book is backend database that hold recipes that were created by spongebob. In order to be able to access the database you must also sign up through OAuth2.
#### Situation
- Spongebob's recipe book is a silly fun way that is meant to show you recipes that spongebob has created in his receipe book. In order to be able to access it you must log in through `OAuth2`. We beleived adding that cartoon element gave the project that creative twist. It also was meant to get us to exercise and implement everything we have learned during our back end module.

#### Task
- When creating this project, as a group we decided that we wanted to use a coding language that we were all comfortable with, so we selected Javascript. In order to be able to create our API, we needed to rely on other frameworks suchs as `sequelize`, `sqlite 3`, `Node.js`, `express.js` and these tools helped make it easier to manage our database. Also in order to try to make our API safer we worked with implementing `OAuth2` because of how easy it is to implement into projects. On the `OAuth2` website you can easily configure the app to your API. 

<img width="800" alt="Wireframe" src="https://github.com/AddyRdz/Final-Portfolio/assets/95986357/32523a23-4d8b-4fe1-a873-11a1e03a69a4">

#### Action
- In order to create this API, our team mostly worked through peer programming. Our focus was trying to get an MVP product and felt that would be better accomplished in teams of two. We also made the decision that each merge needed to be approved by another team member to try to keep mistakes down. 
- On this API I focused on creating the POST route and afterwards testing to make sure that it worked. When doing this I realized that I could not get the result I wanted on Postman and realized that something must've been off. After looking over the code everything seemed to be right but I was still not receiving the correct results on Postman. After connecting with my team and the my multiverse coaches it came to our realization that the middleware was not at its proper place but after correcting it, it was easy to add the other routes and test using Postman. I was also able to create our Postman API documentation.
<img width="800" alt="Project Board" src="https://github.com/AddyRdz/Final-Portfolio/assets/95986357/f98a32f6-25b8-4740-9f5f-02cf238e1b1f">

#### Result
- In end, Spongebob's recipe book turned out to be a simple API, that had the beginning stages of `OAuth2` implementation. Our API gives the user the ability to `post`, `delete`, `put`, `edit`, and `get` all the recipes in the recipe book. We also were able to implement `OAuth2` where the user has to log in with their google account in order to gain access to the recipes that are available. Future versions of the app can allow only authorized users access to their own recipes and other protected functions. 
- I learned in this project that project planning is crucial when dividing our the work and to remember that it is easier to add to a project once you get to MVP. 
<img width="800" alt="Postman" src="https://github.com/AddyRdz/Final-Portfolio/assets/95986357/9c850a43-df06-4887-99b4-54c4f49214ad">

## Technologies 
- Javascript
- OAuth2
- Sequelize
- sqlite 3
- Node.js
- Express.js
- Postman

- Dependencies
  *  `npm install`
  *  `npm install sequelize`
  *  `npm install sqlite 3`
  *  `npm install express-oauth2-jwt-bearer`

## Competencies
### JF 1.5
- Knows how teams work effectively to produce software and how to contribute appropriately
- As I mentioned before, we spent the majority of this project working in teams and peer programming. It is very important when peer programming to follow along with whoever is coding and talking through issues that might come up. I spent a lot of time checking on each other and making sure we were able to get through any problems we might be having. For example during our Multiverse meetings we would go over each others task and give updates on how everything was going. This made us be sure that we were contributing and staying on task.
- In order to be succesfful a lot of time is spent on communicating with each other and understanding how each person works. Once that was determined we were able to be very productive during our meeting times.

### JF 1.6
- Shows curiosity to the business context in which the solution will be used, displaying an inquisitive approach to solving the problem. This includes the curiosity to explore new opportunities, and techniques; the tenacity to improve methods and maximise performance of the solution; and creativity in their approach to solutions.
- As a team, we were all struggling to decide what exactly would be our MVP. We knew we wanted to create an API but we were struggling to see how we would implement our authorization efforts. We spent so much time trying to focus on how we were going to be able to show what we learned from authorization vs authentication module that we were ignoring a very simple solution that was available to us. I realized that setting up our API with `OAuth2` would fulfill one of our tier goals for our app. I mentioned that this might be our best solution and would not leave us in a time crunch.
- As a team we set up an OAuth account and configured the necessary settings to our API. After testing and making sure that our API would not reveal information unless you were logged in, we knew that it was a success. In order to configure the app, we had to include all our secrets into an `.env` file and also select some settings from the OAuth site. In the end we were able to be less fixated on trying to force something that had an easier solution. Sometimes it is better to think outside the box. 
