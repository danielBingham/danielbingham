# Hi :wave:, I'm Daniel (or Bing)

I'm a software engineer from Bloomington, Indiana.  I've been writing code
since  1998 (I was 13) and spent my high school years hacking on a Multi-User
Dungeon in C.  I went to Skidmore College from 2005 to 2009 and studied Physics
and Computer Science, graduating in 2009 with a double major.  Since then I've
been working as a Software Engineer.  I have 10 years professional Full Stack
experience and 5 years DevOps and Engineering Management. 

When I'm not writing code I spend a lot of time working on municipal policy
with my local government and helping out with non-profits and cooperatives.
I'm particularly interested in housing, sustainability, and climate change.
Sustainability of the food system was my primary focus for a long time and a
lot of my early software side projects were in that space.

For the last two years I've been heavily focused on finding a way to achieve
Universal Diamond Open Access of the Scientific literature.  We can't write
accurate municipal policy if our policy makers don't have access to primary
sources. Right now, they don't. I took a few shots at launching a startup
around this, but no luck. So I'm taking a break from it. It's a really hard
problem to solve.

You can find links to my other profiles in the sidebar.  I'll use the rest of
this space to add some context to my repos.

## Projects

**Peer Review / JournalHub** 

Repo: [danielbingham/peerreview](https://github.com/danielbingham/peerreview)

Tech Stack:
- Frontend: React/Redux
- Backend: Node.js / Express
- Infrastructure: AWS, Terraform, Kubernetes, Github Actions

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
[JournalHub](https://staging.peer-review.io). I still think that approach is
viable, but it can't be bootstrapped. It needs to be non-profit to work, and I
haven't been able to get non-profit funding. So it will likely remain a side
project for the forseeable future.

**MuddyReality.py / MuddyReality** 

Repo: [danielbingham/MuddyReality.py](https://github.com/danielbingham/muddyreality.py), [danielbingham/MuddyReality](https://github.com/danielbingham/muddyreality)

Tech Stack: Python (MuddyReality.py), C++ (MuddyReality)

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

**vimrc.vim**

Repo: [danielbingham/vimrc.vim](https://github.com/danielbingham/vimrc.vim)

I'm a vim user and this is my `.vimrc`.  I keep it here so that it's easily
portable between machines.  Feel free to grab anything that looks interesting!

<details>
<summary>Defunct Projects</summary>

**Fridge to Food**

Repo: [danielbingham/fridgetofood.com-old](https://github.com/danielbingham/fridgetofood.com-old), [danielbingham/fridgetofood.com](https://github.com/danielbingham/fridgetofood)

Tech Stack:
    Frontend: 

</details>
