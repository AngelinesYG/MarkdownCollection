# Mom Blog
![Mom Blog](https://i.imgur.com/RZZwuMb.png)


# About 
Mom Blog is a website built with moms in mind. Designed to allow moms to create an annonymous account and safely vent by writing abou their struggles and wins as moms, without the fear of being judged or criticized. 
Mom Blog works as a blogging site where the user has to create and account and log in to write their "vent" blog, as well as read other moms' blogs. 

... User Features ... 
 + User registration/Authentication 
 + Basic chat (future improvement)
 + Create/ Read/ Update/ Delete for logged in users
 + Comment on other's blogs (future improvement)
 + Upload picture to profile (future improvement)

## Installation Requirements via npm
... Dependencies ... 
+ express 
+ express-session
+ ejs 
+ method-override 
+ mongoose 
+ static (for use with public folder)
+ dotenv
+ bcrypt (for authentication)

... Third Party Dependencies ... 
+ mongodb Atlas (Atlas database connection via connection string. This will run mogo and mogod via the Atlas server, rather than on your local machine) 
+ Postman (Used to manually test and input database data)

### If cloning this application 
Sign up for mondodb Atlas, replace all the tokens required for the third party services listed above (such as connection string, which will be specific to your account and needs to be set up in your .env with an environmental variable), and set up your configuration to mongodb variable created in your .env file. 

npm install 


## Assignment Specifications 
+ Basic web application with CRUD functionality using Express and ejs. Database to be hosted by mongodb Atlas and deployed to Heroku. Readme.md must include explanation of project stating "What went well", "What didn't go well", "Future Improvements". 


### What Went Well 

The initial set up and the fact that I liked this new tech stack helped bring about a more smooth start and development structure to the project. I knew what I wanted to build and making a wire frame provided good guidance. 

On the very last day of the project I was able to accomplish authentication. It was something that had been on my mind since the start of the project but was afraid to try it. I had tried it previously during a homework assignment and couldn't get it to work. I had also heard of numerous classmantes spending days tryng to solve bugs when trying their authentication. I followed a class video where my instructor showed us how to do it and I finally got it to work. I couldn't believe I did it. It felt awesome.

### What Didn't go Well 

I struggled A LOT the first two and a half days. I kept getting bug after bug and became super frustrated. I felt incompetent

The bugs were very weird at first. Something about no engine node, even though it was clearly in the package.json. The error didn't seem to very specific and took hours to figure out. Turned out to be a coma! a comma where a period should go!

The next crazy error was due to files getting mixed up when I tried to rename my project. (Or at least I think that was the reason). That one also took a very long time to figure out because when clicking a link to the question and answer page, it kept saying there was an error on a different file which was fully functional. It didn't make any sense at all.


### Future Improvements

The application will receive improvements in the future. Such as; 
+ Better UX/UI (plans for connecting with a professional UX/UI developer for guidance) 
+ More mobile and table friendly. 
+ Better authentication settings and Related models so that users have their own posts. This way only logged in users can add, edit, and delete their own posts, and not anyone else's. 
+ Friends feature. Moms can befriend other moms in the site
+ Basic chat. Moms can chat with other moms right on the app. 
+ Comments on posts. Moms can leave each other comments for support and encouragement. 

### Personal Thoughts 

Inspite of everything, I had fun with this project. I was able to be creative and incorporate some of the things I love doing, which is writing. I got some other moms involved by asking them to write a blog for me so that I could put it on the page. And even thought I know the background images are kind of annoying to look at, I thought they were funny and wanted to incorporate them in some way. I tried doing hero images with them, but I was having a lot of trouble moving the forms down to the bottom, so I just ended up giving the forms a plain color background and leaving the images below. I really wanted funny backgrounds because of the type of site that it is. Because mom's sometimes need a good laugh and to see memes like that is often very funny. But I didn't expect for the background to be repeated like that and I had a lot of trouble adjusting them. I would also make the edit and new pages better and make the box where they enter the forms bigger. I remember we learned that recently, I just didn't have enough time.

This is a project that I would actually like to turn into a real website. Like an outlet for moms to vent and find support. So there will be a lot more thought going into the "future improvements" part. I've recently considered putting together a team at some point to see this project through. 

