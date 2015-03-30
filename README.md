Profile of Michael Welch
============

Summary
-------

I have 19 years of development and IT experience and 3 years of formal leadership experience. I bring a unique mix of skills as I've contributed, led, mentored and taught. Ihave an educational background in engineering, computer science and business.

My passion is for developing clean quality code that is easily maintained and
enhanced and for mentoring others to do the same. I've found that one of the best ways to design good code is to test it. Both the practices of unit testing and automated acceptance testing require that code exhibit characteristics of clean code; and when a design is found to be lacking the
suite of tests make it safe to refactor as necessary to improve the design.

I have 3 years of agile experience. 

Career
-------------

### Johnson Controls ###

I've worked on many releases and features of building automation system and security & fire systems over 13 years. The majority of 
that experience involved the following technologies: C#, Java, Sql Server,
web services. 

#### Highlights ####

* Implementation of binary reader and writer classes in Java and C# that support BACnet encoding. (I later wrote [Haskell version](https://github.com/michaelgwelch/bacnet) on my own time that I can share.) This was supplemented with a testing framework and excellent documentation. The testing framework was virtually identical in Java and C#. This is a highlight because it represents a complete framework (much of it done on my own time), that substantially added to the convenience of writing services for our building automation system. It also contains clean code with a full suite of unit tests.
* Introducing unit testing, refactoring, and clean coding through mentoring, code reviews, and study groups. Two repositories ([Refactoring](https://github.com/michaelgwelch/Refactoring) and [Brainmess](https://github.com/michaelgwelch/brainmess)) were used as part of Refactoring study as well as Martin Fowler's book. I've found the books Clean Code and Clean Coder to be useful. This is a highlight because thru these groups (and my teaching experience) my own skills and confidence grew considerably.
* A language for expressing constraints and a compiler for generating code to enforce them. This is a highlight because it was an example of taking theory I had learned in grad school to solve a difficult problem in a new way. Previous attempts to enforce constraings involved large methods and classes with thousadns of lines of code and hundreds of conditionals and switches.
* State machine engine: We had a goal of trying to ease the complexity of writing concurrent services. To that end we decided to model our services as state machines and needed an engine to run them. I implemented the state machine engine in .Net but compiled and tested on both Windows and Linux. This is a highlight as it required a unique set of automated tests to check for race conditions. It was thru stress testing on multiple platforms that I was able to uncover defects in my implementation that only showed up when run with Mono on Linux. 
* MMS: Metasys Management Services is a framework for distributed communication between Metasys controllers. I was a member of the team that designed and implemented. This is a highlight because it allowed us to scale up a system from a couple dozen controllers to hundreds of controllers. This change allowed us to move from a primarily polling set of services to subscription/push services. The system also allowed us to hit key CTQs (Critical to Quality) metrics (like a change of value in a sensor propagating all the way from the sensor thru multiple controllers to the user interface in under 5 seconds. No polling solution could handle this and any attempt at it would likely stress the server too greatly.)
* Reusable controls for Graphics+: Our program has struggled to write reusable components. Often times, to meet deadlines useful abstractions are left out of components and therefore they are constrained to their single purpose useage. This is a highlight because I designed and oversaw the development of truly reusable graphical controls. They could be resued like typical controls (text boxes, etc.) but also as "smart controls" they could be resued across programs (building automation, or security & fire)
* Pushing Linux early: Many of our products have been subject to Windows licensing. Early in my career at Johnson Controls I became aware of Linux and led a skunkworks lunch-time group to port our native code to Linux to prototype a non-windows solution. This is a highlight 
* Pushing Distributed Source Control: When Linus Torvalds invent git, I wanted to use it. When GitHub was invented I wanted to use it. When I finally got my own team I was able to select these tools and prove how superiour they were especially in relationship to the control system used by other projects. Now most projects are looking to move to GitHub over the next year. This is a highlight because it showcases my patience as I waited for the right time to try something. 


#### P2000 User Interface ####

Technical lead of the P2000 user interace team. The team consisted primarily of consultants all of us new to the P2000 product. My role consisten primarily of high level design, mentoring a team of 7, implementation, and lots of code reviews. Technologies used were HTML5, JavaScript, and ASP.Net MVC.

#### Graphics+ Feature ####

For two years I served as the technical lead for our Graphics+ feature of our
building management system. The tool allows a customer to build "smart"
graphics to monitor and command their building control system. Required
the creation of 300 custom WPF/Silverlight controls. These controls also needed
to work seamlessly in a layout tool (think Blend) and allow these controls to be bound to real-time information (thermostats, damper positions, etc.)

The team I lead grew to be over 20 people working on the controls, the editor, runtime data-access, etc. The technology was C# and WPF/Silverlight and accessing real-time data thru web services and historical data from SQL.

Key aspects of my development role: design pattern for all the controls, design for 
run-time data access, and development in data access.

#### Ready Access Portal ####

Worked on data access for user interface for building automation system. Worked on caching commonly accessed data.


### SysLogic Projects ###

I was a Senior Consultant from 1999 - 2002. I developed in Visual Basic, C# and Sql Server for various clients. I also did project management for one project.

My last client assignment was for Johnson Controls working on the first release of building automation system. Based on the quality of my work, I was hired as a permanent employee.

### Procter & Gamble ###

I was a Systems Analyst from 1992 - 1997. Primary duties included requirements analysis, project management, system support and some development for ERP type systems: production planning, material purchase planning, and warehouse utilization planning.

Management Experience
--------------------

In the first 9 months I was responsible for forming the team, selecting
tool-chain and process, high-level design, and ultimately delivering the first
release of the new user interface. The backend was written in C# and 
used ASP.Net MVC stack. The frontend was written in HTML5 targetting modern browsers. Key libraries used were jQuery and Knockout.

I was promoted to engineering manager soon after this period and my role became
more one of recruting, management, and mentoring. I'm proud of the achievements my team achieved during this time: TDD (high unit test coverage), BDD (they championed it, while I had to smooth over the initial fears that this was taking too much time), simulator to facillitate BDD, the use of virutal machines for build servers, automated
test servers, demo servers, etc. We also released 2 more versions of the UI.

In the last year we rolled out SAFe to all the teams. 

One key challenge we've had to address is how do we set long-term expectations on what features will be complete 6-12 months in the future. The other key challenge we've solved effectively is how to demonstrate quality of feature every 2 week; and this has been accomplished with a high level of automated acceptance tests.

Teaching Experience
---------------

I have taught two courses at Milwaukee School of Engineering: Data Structures and Software Development I. 

Work Experience
-----------------

* Johnson Controls, 2002 - Present (software engineer, engineering manager)
* SysLogic, 1999 - 2002, Senior Consultant
* Procter & Gamble, 1992 - 1997, Systems Analyst
* Milwaukee School of Engineering, 2007, 2009


Who am I
-------

Favorite Language: Haskell

Favorite Tool: git/GitHub

Markdown, Latex

Prefer strongly typed languages (probably because of my academic interests in type systems), but can appreciate the loosely typed like JavaScript (I guess because I'm fascinated by the lambda calculus)

A few of my scribbles can be found at loominate.net

I've answered a few questions at StackOverflow.

I've got some code at github.com/michaelgwelch (Some good, some not so good). I'd love to explain to you which is which and why I feel so. (Contributed a little to other projects, very minor. Always interested in doing more.)

I was even published once in an early edition of Visual Studio Magazine.


Education
-----------

* M.S. Computer Science, University of Wisconsin - Milwaukee
* M.S. Business, University of Wisconsin - Madison
* B.S. Electrical Engineering, University of Wisconsin - Madison

Hobbies
--------

In the last couple of years I've taken an interest in physical fitness: I've recently completed my first two half-marathons, a Rugged Maniac and a Tough Mudder. I'm currently training for my first marathon.

I enjoy keeping up with tech industry: favorite blogs: functional programming, apple blogs, etc.

Enjoy new languages and proof languages (see twelf, coq)

On the Web
---------

*Loominate* I have a presence on several websites. My own blog is at [loominate.net](http://loominate.net). There I occasionally write about software development, computer science and math.

*GitHub and Bitbucket* I have several repositories on GitHub and Bitbucket. I use them to store my work as I learn new topics (a new language, a computer science topic, or even math); and even my blog is there. Of note is a repository that I use for a study group on Refactoring. The code there is verbose as the emphasis is on learning to refactor and doesn't intent to be pragmatic.

*Stackoverflow* I've asked and answered a handful of questions. http://stackoverflow.com/users/697188/michael-welch

Favorite Resources
----------------

Refactoring

TDD by Kent Beck

Clean Coder

Clean Coding

