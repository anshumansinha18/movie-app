# Urban-views

## Project Work by:
#### Jay Shrivastava : 18105126003
#### Anshuman Sinha : 18105126025
#### Saket Kumar Singh : 18105126055
#### Swaranjali Shanker : 18105126013


A Full stack MERN website for movie theatres where user can search for movies and filter by rating and genres that are available,
and admin can add movie to the list and much more.
<img width="1438" alt="ss" src="https://user-images.githubusercontent.com/64154442/127747796-e218d073-5bc7-4781-aea9-c40d96261f6b.png">
<img width="1438" alt="ss" src="https://user-images.githubusercontent.com/64154442/127747778-52ff0d33-a1e5-4e61-8b2d-22a8e19cb07c.png">

<img width="1438" alt="ss" src="https://user-images.githubusercontent.com/64154442/127747782-37b7ec31-bb6f-4610-ba22-7ef987ffd639.JPG">
                                
<img width="1438" alt="ss" src="https://user-images.githubusercontent.com/64154442/127747780-962a2e87-05b0-4826-8bc7-549151084dad.png">

<small>This project will be completed and hosted very soon! </small>

<h2>Installation </h2>

Use the package manager [npm](https://www.npmjs.com/) to install Urban-views.
Setup the project and install the packages by running: 
```bash
npm run setup
```
 Run project with command
```bash
npm run dev
```
 
<h2> Built with  </h2>
<ul>
  <li>FrontEnd: <b> React.JS, Redux Library, Bootstrap, HTML/CSS </b></li>
  <li>Backend:  <b> Node.JS, Express.JS </b> </li>
  <li>Database: <b> MongoDB, Mongoose </b> </li>
</ul>

<h2> Features </h2>
<ul>
  <li> Sign In / Sign Up / Sign Out the user. </li>
  <li> Recieving a welcoming email when sign-up using Nodemailer. </li>
  <li> Add a new movie to the list.</li>
</ul>



<h2> API </h2>
<h4> Users </h4>
<ul>
  <li> <b>POST</b> /api/users/signup </li>
  <li> <b>POST</b>  /api/users/login  </li>
  <li> <b>DELETE</b>  /api/users/:userID </li>
</ul>

<h4> Movies </h4>
<ul>
  <li> <b>GET</b> /api/movies </li>
  <li> <b>POST</b> /api/movies/addmovie </li>
  <li> <b>DELETE</b> /api/movies/:movieID </li>
</ul>

<h4> Genres </h4>
<ul>
  <li> <b>GET</b> /api/genres </li>
  <li> <b>POST</b> /api/genres/addgenre </li>
  <li> <b>DELETE</b> /api/movies/:genreID </li>
</ul>
