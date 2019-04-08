# We the People
We the People gives voice to 15 million young citizens who don’t yet vote, and all other members of society who can. Citizens can view other citizens in their jurisdiction and assign tickets to them to complete various initiatives they care about. They can also create tickets for themselves and display their progression on them on their profiles.

## Table of Contents
* [Overview](#overview)</br>
* [Tech Stack](#techstack)</br>
* [Setup/Installation](#installation)</br>
* [Demo](#demo)</br>
* [Future Development](#future)</br>

<a name="overview"/></a>
## Overview
We the People was built to:
 * Teach young people the power of voting and enable them to contribute to their communities in ways other than voting.
 * Build awareness of the politicians and initiatives being solved in everyon's communitites.
 * inspire people to not wait for politicians to fix their problems, as creating sustainable communities is everyone's responsibility.

<a name="techstack"/></a>
## Tech Stack
**Frontend:** JavaScript (AJAX, JSON, React), Jinja, jQuery, Bootstrap</br>
**Backend:** Python, Flask, SQLAlchemy, PostgreSQL<br/>
**Libraries:** Chart.js<br/>
**API:** Genius<br/>

<a name="installation"/></a>
## Setup/Installation
On local machine, go to desired directory.  Clone protag repository:
```
$ git clone https://github.com/rbarner14/protag.git
```
Create a virtual environment in the directory:
```
$ virtualenv env
```
Activate virtual environment:
```
$ source env/bin/activate
```
Install dependencies:
```
$ pip install -r requirements.txt
```
Create database:
```
$ createdb music
```
Build database:
```
$ python3 -i model.py
>>> db.create_all()
```
Seed database:
```
$ python3 -i seed.py
```
Run app:
```
$ python3 server.py
```
Navigate to localhost:5000 in browser.

<a name="demo"/></a>
## Demo

https://www.youtube.com/watch?v=PKJS85Cgvd4

**Sustainable development goals.**
<br/><br/>
![SDG](/static/images/readme/SDGs.png)
<br/>

**Initiatives.**
<br/><br/>
![SDG](/static/images/readme/initiatives.png)
<br/>

**Citizen profile.** 
<br/><br/>
![Profile](/static/images/readme/profile.png)
<br/>

**Citizens in the We the People community.**
<br/><br/>
![Citizens](/static/images/readme/citizens.png)
<br/>

**Initiatives completed by SDG and over time.** 
<br/><br/>
![Donut](/static/images/readme/initiatives_donut.png)
![Graph](/static/images/readme/initiatives_graph.png)
<br/>

**Create ticket.** 
<br/><br/>
![Ticket](/static/images/readme/ticket.png)
<br/>


**Thanks for exploring!**

<a name="future"/></a>
## Future Development
* Implement algorithm to suggest causes and initiatives leveraging their favorites.
* Incorporate block chain token disbursement.


