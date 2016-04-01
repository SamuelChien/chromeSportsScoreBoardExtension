**Introduction**

The goal of the add-on is to give users an alternative of viewing a real
time sports score data without the need of switching browsers or tabs.
The add-on should allow users to stream real time score of their
favourite sports team on the side panel. The primary goal of the add-on
is to serve sports data for the users without the need of searching
through google. In other words, the add-on must be easier to navigate
than searching the scores on the website.<span
class="Apple-converted-space"> </span>


**Requirement & Criteria**

Some of the key requirements of the add-on are real time sports data,
intuitive user interface, and accurate information. The main criteria
measurement of the add-on will be judged based on the time users take to
acquire sports data.<span class="Apple-converted-space"> </span>


**Product Market Fit**

The customer validation is done through many iterations of informal
surveys and the result shows that one of the main demands of add-on
users is to be able to improve their workflow while enabling them to
keep up with their favourite sports and the survey has also shown that
many of these users constantly search through google for real time game
scores as well as sports highlights. Moreover, the reviews on the
current version of the real time sports add-on also proved that many of
user’s needs are ignored. In addition, many of the direct competitor
add-ons have shown to be severely outdated with many functionality bugs.
Most recent review from 2015 indicates that users were unsatisfied with
the lack of updates and is looking for alternatives since the add-on
does not work because of a major change in Firefox 29. \[1\] Similarly,
most recent review from 2015 also indicates the users had encountered
some issues when trying to use the add-on where settings menu does not
respond. \[2\]


<span class="s1">\[1\] </span><span
class="s2">https://addons.mozilla.org/en-US/firefox/addon/are-you-watching-this-sports/?src=search</span>

<span class="s1">\[2\] </span><span
class="s2">https://addons.mozilla.org/en-US/firefox/addon/365scores-notifier/?src=search</span>

<span class="s2"></span>

**Target Users<span class="Apple-converted-space"> </span>**

Our primary target users are sports fans who have basic knowledge about
firefox add-ons. The users are scattered throughout the age group with
the majority of users between age 15-25. This add-on will cater to
sports fanatics whether young or old, female or male, student or working
adult who tend to often keep multiple tabs open and need to switch
between them from time to time to be able to check score updates.<span
class="Apple-converted-space"> </span>



**Value Proposition**

Our add-on provides durability, where the user does not need to
painstakingly switch tabs to view the score of their favorite team(s)
when they are using different tabs. We realized how easy this would make
life for sports fans like some of us. We need not to worry about
switching and having a special tab open (thus saving tab space at the
top of the browser) for the score updates because there will be a box
provided with the scores on every tab we are on. Also, we don’t need to
worry about the scores box using up too much space on the screen and
hence, there is no question of it interfering with any other activity we
may be doing on the firefox browser. Furthermore this enables efficient
multitasking while also following your favorite team.<span
class="Apple-converted-space">  </span>Finally, our addon removes the
time consuming task of always having to load the different websites of
different sports. With our addon, you can simply set it up once and it
should always work.



**Technical Components**

This add-on will have a big menu with data of multiple teams and
matches. The user will select the desired match(es) to follow and there
will be a small ticker at the bottom of the screen that refreshes
periodically providing the user with real time updates for that
match.<span class="Apple-converted-space"> </span>





<span class="s2">Front End/UI<span
class="Apple-converted-space"> </span></span>

-   Main View: small relocatable sports-summary window that opens when
    you click on the add-on button.
-   Settings Page: full-size page for editing your preferences and
    choosing what you follow.


Sample UI:<span class="Apple-converted-space"> </span>

![alt tag](https://github.com/csc302-2016-spring/group3/blob/master/doc/phase1/images/image00.png)
![alt tag](https://github.com/csc302-2016-spring/group3/blob/master/doc/phase1/images/image03.png)
![alt tag](https://github.com/csc302-2016-spring/group3/blob/master/doc/phase1/images/image05.png)
![alt tag](https://github.com/csc302-2016-spring/group3/blob/master/doc/phase1/images/image06.png)

<span class="s2">Back End</span>

Code to control what information appears in the summary-window, based on
the user's preferences and the real-time data (i.e. display only recent
scores for sports/teams that the user follows).

Sport Scores API’s

Different API’s for different sports if needed

-   ESPN API
-   MSNBC
-   XML Live Scores
-   ...and much more

Page parser

-   We might create a component that parses sports related pages for
    data we want if we are unable to acquire it through API means. For
    example, fetch data off http://www.livescore.com<span
    class="Apple-tab-span"> </span>



**Team**

The team is formed with skillful front-end designers as well as
competent backend developers. Many of the team members are extremely
knowledgeable in the website development and have few years of industry
experience. The team will be using github as primary source control and
the project will be run under agile development method. We plan to
divide the work based on the skillset of each individual but at the same
time everyone will take part in learning the new technologies we will
work with.



**Risk**

Since all team members’ time schedule are completely different, it is
unavoidable that we will have meeting conflict. Moreover, it is the
first time the team has collaborated as a group, so it might slow down
the development process. We plan to try to alleviate this using a live
group chat as well as dedicating time for stand-up meetings.



In regards to the technological skills needed to make this addon, our
team possesses a good varied skill set however we all will be learning
and working with new technologies so this will definitely play a role in
the speed of development for the addon.



We are hoping to find one API service that is able to provide stats for
most sports. However, progress could slow down if we have to engineer
the code differently for different API’s, though we are willing to do
it.



In terms of the timespan to develop the addon, we plan to develop the
addon in stages. However due to the complications described above a risk
may be that be underestimate the time needed for the addon and might
need to compensate for that later down the road with extra work.



**Personas**

-   Office worker John: John is an avid sports fan and a regular
    office worker. He is a diehard Real Madrid fan. He lives in Canada.
    He follows various sports from all over the world. He wants to know
    European soccer game scores as they come out. His boss expects him
    to stay on top of work at any given time.
-   Student Jake: Jake is a high school student on the football team,
    and loves sports. He follows football, hockey, and basketball, and
    he checks the websites of each league often to know which games are
    coming up and what the scores are in ongoing games. He wishes there
    was an easy way to see all the information in one place whenever he
    is on the computer. Not having to open multiple sites and rather
    just have a place to view them all together would be of great
    benefit to Jake. It would allow him to study without wasting time
    switching between different sports sites. Jake also forgets about
    the matches while studying so this addon will also help him remember
    when the matches are happening.
-   Workaholic Adult Mary: Mary works really hard at her day job but
    when she gets home she wants to check out everything she’s missed.
    Mary wants to read the latest news reports, watch youtube videos,
    and much more. Mary also has a 2nd job in the evening. With the
    little free time she has, while Mary likes sports, she does not want
    to waste time trying to find all the websites that show the scores
    for her favourite teams. Mary wishes there was a way she can just
    concisely pick the teams she wants to follow, and then have scores
    and information about them no matter what she is doing on her
    web browser. With the extra time saved, she can use that time on
    other enjoyable things.



**User Stories**

-   Jake:
   
    As Jake, I’m typically home browsing the internet while studying
    and forget about my favourite sport teams’ matches. I want to always
    have information (and be notified) about current and future games
    happening without needing to look it up so that I save more time for
    studying and additionally don’t forget to watch the match on TV like I
    did the past view times.<span class="Apple-converted-space"> </span>
    


-   John: 
    
    As John, most of the soccer games in Europe are played during my
    work hours. As a working adult and a die hard fan of Real Madrid, I want
    to know the score of any Real Madrid match going on without needing to
    switch away from work related browser tabs so that my boss does not
    think I am distracted and at the same time I can stay up-to-date without
    having to stop working.



-   Mary: 
    
    As Mary, I want to know if any sports teams in Toronto have
    finally won a game. However, I have a very busy life, 2 jobs and simply
    do not have time time to do this by looking through all possible sports
    sites. I want a simple, easy to access way to get update on which teams
    played games today, as well as their scores so that I am not wasting my
    little free time on miniscule inefficient tasks and instead use that
    time for other enjoyable things.<span
    class="Apple-converted-space"> </span>





