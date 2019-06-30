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

18 May

I'm at a friend's place over the weekend and dont have my laptop with me but read articles and blog posts about coding, so my brain is forced to deal with a sibject matter on a daily basis. i just opened the freeCodeCamp email from Thursday and read a blod post written by Vid who taught himself how to code through - among other things - freeCodeCamp. He also mentioned two resources I wasn't familiar with:
- Codewars
- The You Dont Know JS book series

Both of which sound absolutely great! I am going to get on that right away. Of course it is best to have a computer in front of you and write a few lines of code (at least!) every day but for those days and times when your own schedule seems to be working against your coding journey, those resources I can fall back on and practice a wee bit whenever I have a moment to breathe. Plus, I found Vid's story very motivational and it has energised me to code even more now. i admit after the forst few months of the year where I longed to go back home to code for hours on end, now some weeks have crept in where I didn't do much, sometimes the bare 20 minute minimum recommended by Angela, sometimes not even that. But I love it so much and want to keep at it and improve more drastically than I might have done over the last month or so, and Vid's story has motivated me to pursue that :)

19 MAY

So I put my new resolutions to practice right away and started reading the JDKJS. It was written for people who are just starting out with JS - or the first book is anyway - but I have to say although I have done intermediate JS on the Udemy web development course I look forward to building my knowledge of the essentials and understand why things they work they do. Plus, the books give me a chance to learn about JS even on the days when I do more front end development for static websites.

20 May

So as I am going through JDKJS, I am going to take note of the things I am learning as I go along, specifically the concepts I am not familiar with. I am starting with book one, “Up & Going”, and with very basic concepts. Many of those I have used before and I generally know how they work but it’s still useful to have someone go through them in detail and explain everything - I can already tell I am going to pick up a lot of new knowledge, even of concepts I thought I knew well.

What I learned today:
- There are different types of expressions
- Compiler vs interpreter

Different types of expressions

Before, I thought all expressions were just, well, expressions but as it turns out there are different kinds, e.g.

- Literal expression, like the value 2
- Variable expression, like the variable b
- Arithmetic expression, like the multiplication b * 2
- Assignment expression, like the assignment of the result of b * 2 to the variable a in a = b * 2
- Expression statement, like the stand-alone general expression b * 2
- Call expression, like the entire function being the call expression itself like in: alert(a);

The difference between a compiler and an interpreter

I knew that the computer has to translate the code we write in human-legible programming languages (JS, Python, C#) into ones and zeros before it can run the code but I thought this was always done more or less the same way.

I know now that an *interpreter* translates every line of code from top to bottom line by line while a *compiler* translates everything at once so that later when the programme is run, the code the instructions to the computer have already been compiled and are ready to go.

To make it not too easy on us (reasonably) newbies to it all, JavaScript  actually uses a hybrid of the two methods: The JS engine compiles the source code as we go along and the immediately executes it, which gives it the effect of an interpreted code.

Output

Dissecting the console.log() statement, by using the example console.log(b): 
The log(b) is the function call that we are handing the b variable to.
The console. part is an *object reference* where the log(..) function is located.

Input

While the most common form to get input from the user is to have an HTML form and then have JS read and interpret the values that the user puts in, for the purposes of learning JavaScript - especially when working in the developer console of browsers a lot - is the prompt(..) function. The prompt(..) function prints whatever is passed over to it as a request to the user into a pop up window. For example, these lines of code

age = prompt(“Please tell me your age: ”);
console.log(age);

creates a pop up window with the instructions “Please tell me your age:” and a text box for the user to put in an answer.


Once the user submits their answer by clicking “OK” the value they out in is stored in the variable age.

So because our second line of code asks the computer to print the value stored in variable age to the screen, that value is logged to the console.

Operators

Right, I knew the syntax for assigning variables is that you have the variable name on the left-hand side of the equal sign and the value you want to assign o it on the right-hand side (this may also be an expression).

Also, remember to use the keyword var to declare a new variable but you only need to declare it once within the scope of a programme.

var a = 20;
a = a + 1;
a = a * 2;
console.log(a);        // 42 

27 May

Just some freeCodeCamp JavaScriptin' for me tonight. I am having a busy time at work and with organising my international move - not to mention moving out of my apartment and DECLUTTERING my life - I have an insane amount of work and organising to do aside from my day job and some coding. But I squeeze in a few minutes of coding whenever I can and fCC is absolutely perfect for that. Talk about bite-sized chunks of information to absorb. 

Having completed the freeCodeCamp Responsive Web Design Certification - yay me :) I am actually proud of that! - I am now moving on to the JavaScript section of the fCC curriculum. I have covered a lot of JS in the Udemy Web Development course as well but it will serve me well to repeat many of the concepts because learning about them - and even applying them, only  a couple of times as part of a project and then moving on to the next topic on the web development curriculum doesn't really burn them into your brain yet. Or for me it doesn't anyway. I have "a memory like a cullinder", as we say, and need to repeat everything multiple times for my brain to learn it.

So it works out well that I am going through the FCC JavaScript part of the curriculum at the same time that I am reading through YDKJS.

28 May

So Quincy Larson just interviewed Saron Yitbarek on the latest episode of the freeCodeCamp podcast. Her story of how she got into tech and all the things she is working on is really impressive! I also had a listen to her own podcast, CodeNewbie, specifically the interview with David Mallan who teaches the Harvard Uni CS50 course which I began learning with back in 2014 (!). I didn't finish it but I made it through a number of problem sets the summer before my own postgrad degree started. Then the craziness of my own degree kicked in and I spent all my time studying for that. I really enjoyed both interviews though, the one with Saron and the one with David, because listening to these always gets me motivated to continue working on my own coding, even after a day spent working and taking the train to another city for a vocational training course tomorrow.

30 May

Spent a large part of the bank holiday coding and working on my own blog (as well as going through some Udemy lectures) but I forgot to upload my work to GitHub... - so my streak is broken. Again. Not the first time this has happened haha #programmersproblems Oh well, as long as I do something coding-related every day, and on the days wehere I can't / don't have the time to prgram listen to podcasts or read articles on the subject.

1 June

- learning about RESTful APIs as part of my Udemy course on full stack web development

13 June 

Salting and bcrypt

Passwords created by humans tend to be easily hackable because they tend to be short and they tend to be dictionary words.

No matter how insecure the user's password is, adding the salt increases its complexity and its number of characters.

If we use our table from before and salt the users passwords and then create the passwords out of these salts, we can see that the hashes of users 1,2 and 4 (that used to be the same) are now completely different. To each of their passwords we appended a random salt before we hashed them.

The salt is something the user doesn't have to remember and we simply store the salt and the hash in our database. 

However, with the latest CPUs where we can create 20,000,000,000 MD5 hashes per second, it would still be relatively easy to create a hash table using all different salt combinations - even after we increased the complexity of the passwords by adding the salts.

The way we can solve this problem is by using not MD5 as a hashing algorithm but bcrypt, which is valued because it's incredibly slow. Bcrypt is an industry standard hashing algorithm used by developers to keep their users' passwords safe.

Creating a hash table that would take you 3 seconds with MD5 would take you something like 8 months with bcrypt.

Bcrypt also comes with an additional concepts, salt rounds. The more salt rounds you add, the more secure is your password.

Remember Moore's law that says that every year computers get twice as fast and that new power only costs half of what it cost the previous year. Every year you can get more computing powers for less money.

Bcrypt is genius because it lets you set the number of salt rounds. If you set it to 10 rounds this year, maybe next year you set it to 12. Every time you had a salt round, the amount of time it takes to decrypt the password doubles. So every year you don't have to update your algorithm or change your code but simply change one number to keep up with the times.

27 June

Worked through some chapters of YDKJS.

28 & 29

More YDKJS.

30 June

Half marathon and more JavaScriptin'.
