## Popcorn Watch
### Overview
Popcorn Watch is a React front end app that was created during our front end module by Deja Clarke and I. As a user you can search the top movies and shows and get more information regarding the selected movies. 

#### Situation
 - As a team, Deja and I wanted to create a project where we could implement themoviedb.org API. The API itself is an amazing database that has any information that you could think of. It has data on the top movies and shows and is constantly being updated. We thought creating an app that resembled Netflix would be a great way to utilize this API. We really love how on the Netflix app you are shown on the home screen a page full of movies and when you click the movie you are able to get summary info, etc. So it was something that we wanted to replicate within our app. Popcorn Watch app as it stands now, is a great resource for anybody that wants to search for the best movies and shows that are implemented in the moviedb.org API.
#### Task
- Deja and I had just completed the deployment app that we created using React and we thought that continuing on using React would help us establish a solid foundation of our skills. In order to make it a little bit easier on us, we implemented Bootstrap components to help us create a uniform look and feel. Bootstrap has some color limitations so we tried to choose the colors that reflected like Netflix. 
 - At the beginning of our project, we did a lot of peer programming to try to take advantage of the time that we were given on fridays. We decided to keep track of every task on the project board we created on Github and assigned tasks that way. We would meet again on Tuesdays for an half an hour to update each other on our individual tasks and to see how far we had gotten along. It was very important for us to be able to review each others code and set up our Github settings to not let one person merge without their code getting checked by the other person. 


 <img width="1717" alt="Project Board" src="https://github.com/AddyRdz/Final-Portfolio/assets/95986357/318c34f8-4607-4bd3-84c3-b436152dd902">

#### Action
- As a team, we each had different tasks that we were in charge of. I created a profile on the API website in order to be able to receive the API key. After Deja set up a basic react app, she went ahead and set the app up where you could fetch from the API. I realized that our API key was not protected so I changed our files and protected our API key. I also wanted to get more experience in setting up routes in react so I took the liberty of setting up our `routes/home.js` and `routes/shows.js` page. This gave us the opportunity of having multiple pages in our app instead of just the home page. I also added a navigation on `navigation.js` file. Our first nav bar did not have a search section but with the help of bootstrap I was able to implement a search section to our search bar. Deja and I collaborated on creating our logo and I added it to our navigation bar.
- For the most part we did not run into any serious issues until we started setting up a click module that we had where we could not see the details of our movie. I believe the source of our issue was in the css stylin and with the help of David we were able to solve the issue.


#### Result
- On Popcorn Watch you are able to see all the top movies and shows and after clicking the movie or show that interests you, then a box will pop up with information such as the summary, imbd score, and release date. Our goal was to have an app that resembled Netflix a bit and I believe we were able to do that. The Popcorn Watch app displays movies and show posters just like netflix does, and after clicking the item, you get a brief summary which is how it is shown on Netflix. This is great starting point because you can easily add to it, for example create profiles and add authentication to each profile.
- I learned that a lot can be done in a group if there is constant communication and common goals are established. Also sometimes you have to be much more realistic in your expectations and settle on making sure the feature works before trying to improve it. I loved gaining more knowledge on implementing an API and remembered how important it is to keep your api key secure.


 <img width="976" alt="Popcorn Watch Home View" src="https://github.com/AddyRdz/Final-Portfolio/assets/95986357/d5b58381-9577-4c71-a9a7-2d9bbf662891">
   
   <img width="971" alt="View after clicking movie" src="https://github.com/AddyRdz/Final-Portfolio/assets/95986357/7199b666-8fce-46cc-871f-39bff3e6296d">

## Technologies
- React
- Bootstrap
- React Router
- Logo Builder
- https://www.themoviedb.org/

- Dependencies
 * `npm install`
 * `npm start`

- Deployment Tools
  * Netlify

## Competencies
### JF 1.5
- Can develop effective user interfaces				
- When first planning Popcorn Watch we knew that we wanted the app to have a cohesive clean feel. Boostrap currently offers different navigation bar components and it was up to me to select the correct one that would be effectively used. in order to choose which one was best I had to compare and see the pros and cons of each component offered. I knew it was important to select a navigation bar that had a search feature because we wanted the user to be able to search shows and movies rapidly. List the full text of the job function first
- Eventually I choose the navigation bar we used because it has a search component and did not have too much going on. Describe a situation where you demonstrated  this job function.
- This helped me learn that its important to take the user into consideration when applying components and what their main purpose is.

### JF 4.1
- Can interpret and implement a given design while remaining compliant with security and maintainability requirements.						
- As I mentioned before, when we first implemented our API, we realized that we made ourselves vulnerable by not creating a `.gitignore` file that would hide our API key in an `.env` file. Unfortunately if you commit your sensitive information and push it up to Github you are at risk of getting your API key stolen and used without your consent. 
- After we found our mistake I immediately suggested that we correct our issue and remove any traces that showed our actual API Key by creating the `.env` file and by monitoring any warnings we could receive on our Github repo.
- I have found myself before making this mistake and it was good to catch it before it was exposed much longer. This lesson is a great experience that will make sure I am following and taking care of security senstive information. 


  
