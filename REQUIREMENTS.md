# WebApp Requirements
## Appropriateness

The app should be appropriate for use by adults, but viewable by all ages. The app should not encourage or enable violence or discrimination, intentionally or otherwise. 

## Theme
Knox or college-student oriented themes are encouraged. Try to create an app that you could envision using yourself. 

## Functionality
Your app should incorporate the following basic functionalities: 
### Login
Your app should have a login mechanism with a simple profile. Functionality of and/or access to parts of the site should be restricted only to users who are logged in.  Login should be provided by OAuth using a Google or GitHub account.

### Persistence
Your app should incorporate some element of persistence. Actions made by users should remain - eg, posting a comment, creating a list, etc. 
You do not need to implement this until Sprint 2. 

### Backend 
- Your app should use python and Flask on the backend.
- Your app should use a database 
- The entire app should be Dockerized, either as a single container or multiple containers for each service. We will cover the basics of Docker in class.

### Frontend
Your frontend should be written in HTML, CSS, and Javascript. While it is not necessary to use any major framework (React.js, Vue, Angular, etc) it is recommended. Your app should use a CSS framework such as Bootstrap or TailwindCSS. Your frontend should be able to be displayed on a desktop browser and a mobile device (Sprint 3). The mobile device may have reduced functionality.

### Public API calls
Your app should make API calls to some remote service not controlled by you. This remote call can be used to implement login functionality and/or persistence.  This may also be used to display information about the world (eg, if you are building a movie recommender system, you will need to access TMDB API. If you wish to display stock prices, you may need to access the Yahoo Finance API)

### Availability
Your app should be available online starting from the end of Sprint 1. You can use GitHub pages to host your front end, but you need to have some hosting service for your backend. DigitalOcean, Oracle Cloud Infrastructure, and AWS among many others all have free tiers that might be useful. The best option changes from year to year and I encourage everyone to share information between teams on this.  

### Multi-user environment
Your app should create an environment that users can view content or interact with each other.  That means that each user should be able to see something from other users.

## Scope
Make sure you take into account the time you have available for each sprint. You may have a grand plan, but you must make sure that you have a viable demo at the end of each sprint. By the same token, make sure that your app is of suitable complexity for 7-8 weeks of coding by 3 developers. I am estimating 13*3*2=78 hours per sprint of work, including class time. This includes time you spend on your continuing mission, to solve strange new bugs. To seek out new APIs and new coding tools. To boldly develop what you have not developed before. 

## Original Work and Effort
While your app may be very heavily inspired by other apps, your app must be original work. By this I mean that you may not implement any app that has a publicly available tutorial. You may, however, use tutorials to help create small elements of your app or to connect existing elements. As a rough estimation, if a single tutorial walks you through more than a couple hours of work it is probably too much. 

