# Hi :wave:, I'm Daniel (or Bing)

I'm a software engineer from Bloomington, Indiana.  I've been writing code
since I was 13 (1999) and spent my high school years hacking on a Multi-User
Dungeon in C. I went to Skidmore College from 2005 to 2009 to study Physics
and Computer Science. I graduated in 2009 with a double major.  Since then I've
been working as a Software Engineer. I have 10 years professional Full Stack
experience and 4 years DevOps and Engineering Management. 

When I'm not writing code I spend a lot of time working on municipal policy
with my local government and helping out with non-profits and cooperatives.
I'm particularly interested in housing, sustainability, and climate change.
Sustainability of the food system was my primary focus for a long time and a
lot of my early software side projects were in that space.

For the last two years I've been heavily focused on finding a way to achieve
Universal Diamond Open Access of the Scientific literature.  We can't write
accurate municipal policy if our policy makers don't have access to primary
sources. Right now, they don't. I tried to build a non-profit startup to solve 
the problem, but couldn't find funding for it.

You can contact me at my [website](https://theroadgoeson.com), through my email
(linked in the sidebar), or any of the socials linked in the sidebar. My full
CV, including my volunteer work, is [here](https://theroadgoeson.com/cv).

## Active Projects

These are recent projects or active side projects that I'm still chipping away
at.

### Peer Review / JournalHub 

**Repo:** [danielbingham/peerreview](https://github.com/danielbingham/peerreview)

**Tech Stack:**
- Frontend: React/Redux
- Backend: Node.js / Express
- Database: PostgreSQL
- Infrastructure: AWS, Redis, Terraform, Kubernetes, Github Actions

This is my attempt to build a universal scholarly publishing SaaS platform.  I
started with a crowdsourcing concept.  The idea was to use a StackExchange-like
reputation system linked to Github-like review tooling to effectively replace
the role of the journals.  That was called [Peer
Review](https://peer-review.io).  After building a beta and collecting user
feedback, it became clear that wasn't going to work for a myriad of reasons.

But another idea seemed like it just might, which was basically building Github
for Journals. A super user-friendly SaaS platform that made it very easy for
journal editorial teams to run their operations with out the need of a
commercial publisher. I spent some time exploring that pivot, which I called
[JournalHub](https://staging.peer-review.io). I was unable to fund it.  It 
needs to be a non-profit to work, can't be bootstrapped, and non-profit funders 
aren't funding this.  So it has been demoted to side project.

### MuddyReality.py / MuddyReality 

**Repo:** [danielbingham/MuddyReality.py](https://github.com/danielbingham/muddyreality.py), [danielbingham/MuddyReality](https://github.com/danielbingham/muddyreality)

**Tech Stack:** 
- Python (MuddyReality.py)
- C++ (MuddyReality)

This is my on-going Multi-User Dungeon project.  I learned to code by building
a Multi-user Dungeon, and I still really enjoy the format.  You can build
really in-depth worlds with out needing to be a graphical artist.  MuddyReality
was my attempt to modernize and update the game engine I built in high school.
I didn't get very far before other projects drew me away.  I haven't come back
to it since ~2013.

A couple years ago, I wanted a fun project I could use to get some practice
with Python.  Writing a Multi-user Dungeon engine was the obvious choice.  It
started out as just an execuse to play with Python. But as it grew, I realized
I was once again re-implementing my ideal MUD engine: a hyper-realistic, open
world survival crafting game.  It was MuddyReality in Python.  So I renamed it and
made it explicit.

I'm not sure how Python performance is going to hold up once it's at scale and
under load.  So right now I'm thinking of it as the skunk works for
MuddyReality v1.  I'll use it to play with mechanics and approaches in a rapid
development context and then translate them back to C++ once I've got them
tuned.  The idea is that both the Python engine and the C++ engine will be able
to use the same data files, so the world generators can stay in Python (since
they don't need to be as performant).

The generators and data files are also designed so that it can be readily
converted to a graphical engine.  My [brother](https://github.com/nbingham1)
has a knack for graphics and his high school project was the [Blaze
engine](https://github.com/nbingham1/Blaze).  So we might eventually translate
the data files to Blaze and create a graphical version of the game.  This is
probably a lifelong project that I'll toy with in fits and starts.  Maybe my
kids can hack on it too some day.

### vimrc.vim

**Repo:** [danielbingham/vimrc.vim](https://github.com/danielbingham/vimrc.vim)

I'm a vim user and this is my `.vimrc`.  I keep it here so that it's easily
portable between machines.  Feel free to grab anything that looks interesting!

## Defunct Projects

These are projects that I worked on at some point and still keep the code on
Github for posterity's sake.  Some of them might be reactivated if I regain
interest.

<details>
<summary>Defunct Projects</summary>

### Forest to Farm

**Repo:** [danielbingham/foresttofarm.org](https://github.com/danielbingham/foresttofarm.org)

**Active:** Jan 2015 - Sep 2016

**Tech Stack:**
- Frontend: Javascript (Backbone)
- Backend: Ruby (Rails)
- Database: Mysql
- Infrastructure: Chef, Linux, Linode

This was a side project I worked on while on sabbatical from Ceros and also
doing a lot of volunteering for various non-profits and cooperatives. I used
it to learn Ruby and Rails. I got reasonably far with it, but the primary
challege was data ingestion. I put it down when I returned to Ceros.

### Farm to Fridge

**Repo:** [danielbingham/FarmToFridge](https://github.com/danielbingham/farmtofridge)

**Active:** Dec 2011 - May 2012 

**Tech Stack:**
- Frontend: Javascript (JQuery)
- Backend: PHP (Zend)
- Database: MySQL
- Infrastructure: Linux, Linode

This was an online Farmer's market that had planned support for individual
farms, CSAs, or whole markets with multiple farms. I was working with
Bloomington's Local Grower's Guild who were attempting to fundraise for it.  I
got a functional prototype completed, which was demoed a few times, but funding
never came through.  I put the project down when I joined EllisLab.

### Fridge to Food

**Repo:** [danielbingham/fridgetofood.com-old](https://github.com/danielbingham/fridgetofood.com-old), [danielbingham/fridgetofood.com](https://github.com/danielbingham/fridgetofood)

**Active:** May 2010 - Dec 2010

Tech Stack:
- Frontend: Javascript (JQuery)
- Backend: PHP (Zend)
- Database: MySQL
- Infrastructure: Linux, Linode

My first attempt at a startup.  This was a recipe sharing site, originally
using a StackExchange-like reputation system. (What can I say?  I think
reputation systems are cool!) This had a fully functional MVP beta. But I was
never able to market it successfully or build any kind of traction. I put it
down when I joined Ideacode.

</details>
