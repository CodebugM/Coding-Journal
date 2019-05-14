# Coding-Journal
A journal-like log documenting my self-taught journey learning how to code


The description line pretty much says it all. This is my coding journal where I document what I do and learn as I teach myself how to code. 

I am mainly working through the Udemy "Web Development Bootcamp", which is taught by Angela Yu - and which is absolutely great! I HIGHLY recommend it!! You learn a TON - and through freeCodeCamp's various certifications.

EVERYONE out there seems to agree that you should keep a coding journal and "learn in public", as they say, so here we go. I initially started keeping a log of sorts about everything I learn in OneNote, which I can recommend whole heartedly because it lets you keep screenshots and take detailed notes, but I want to keep a parallel journal/log (journal sounds very much like "diary", to my ears anyway) and this is going to be focused on coding rather than on "Dear Diary" moments ;)

27 April

Today involved travelling back from Georgia to Germany and that meant that I did not have any time to code. So I decided to review the lessons on databases from Udemy. Besides freeCodeCmap, I am also working my way through Udemy's "The Complete 2019 Web Development Bootcamp", which is taught by Angela Yu, and which I really highly recommend. She is GREAT! You learn so much. She goes through front and back end development in a lot of detail with loads of projects you do along the way (I am really fond of this course! It is the one course that has got me stuck with coding) - anyways, during the backend part of the course you learn all about mongoDB and mongoose, so I reviewed all my notes that I was taking while working through the lessons.

14 May

After a number of days of uploading and updating js and ejs files, the time has come again to update my coding journal. Today, I have no files to upload because I have been following along and taking notes from a Udemy lesson on how to set up and connect to the monogDB Atlas cloud service so I can host my todo list app online and not just locally. I am taking a lot of time going through videos because I take meticulous notes as I go through them - I have a memory like a goldfish and I won't remember tomorrow what I did, let alone why, so it's important for me to take notes, so I can review them when I get the chance like on days I can't code or whenever I want to review how I did things.

The things I have completed during today's coding lesson:
- Set up a free MongoDB Atlas account
- Create a mongoDB admin user in my cluster0 
- Add a whitelist entry
- Connect to the cluster through the Mongo Shell
- Link up to the monogDB server on Atlas through the terminal to have an active session with the mongoDB shell running on our Atlas cluster
- Access our online cluster through the terminal
- Create a test database, collection and document in our mongoDB cloud and access it from the terminal to double check we are actually connected to the cluster we see in the cloud

Terminal command:
MongoDB Enterprise Cluster0-shard-0:PRIMARY> show dbs
admin   0.000GB
local   3.821GB
testdb  0.000GB
MongoDB Enterprise Cluster0-shard-0:PRIMARY> use testdb
switched to db testdb
MongoDB Enterprise Cluster0-shard-0:PRIMARY> show collections
test
MongoDB Enterprise Cluster0-shard-0:PRIMARY> db.test.find()
{ "_id" : ObjectId("5cdb19091c9d44000000267d"), "newData" : "Welcome to your database!" }

