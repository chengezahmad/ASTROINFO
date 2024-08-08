# ASTROINFO

<p>
ASTROINFO is a program built to display information 
on asteroids and other smallbodies. It sources data from 
NASA's Smallbody Database, NeoWs API, and CAD API to get
information on properties, orbital info, and approach dates.
</p>
<h2>
ASTROINFO.py
</h2>
<img src="https://raw.githubusercontent.com/chengezahmad/ASTROINFO/master/assets/ASTROINFO_window.png" alt="ASTROINFO Window">
<p>
ASTROINFO.py is the main file. Enter an asteroid ID to see its physical properties, orbital properties, 
and approaches in the customtkinter window.

You can also enter two dates in the "Find Close Approaches by Date Range" section to find asteroid approaches to Earth
within that range.
</p>

<h2>
AOS.py
</h2>
<img src="https://raw.githubusercontent.com/chengezahmad/ASTROINFO/master/assets/AOS_window.png" alt="AOS Window">
<p>
AOS.py (ASTROINFO Orbital Simulation) is a simulation that displays the positions of celestial bodies at a given time. 

Soon, in version 1.2.0, AOS will be linked to ASTROINFO to display an approach that the user may be interested in.
</p>
<h2>
classes.py
</h2>
<p>
The classes file is the backbone of the program. It contains the two classes that are used for 
getting information on the asteroids that the user inputs. Whenever an object is made a member
of the Asteroid class, it gets new properties that can be used to get data on the asteroid that
the user put in.
</p>
<h2>
NASA API Keys
</h2>
This program uses NASA APIs, which means it requires an API key to use. I don't want to leak my
own API key out, so I would heavily reccommend get your own. 

Use the link <a href="https://api.nasa.gov/">here</a>
to go to NASA's website and generate an API key that will be emailed directly to you. 

<img src="https://raw.githubusercontent.com/chengezahmad/ASTROINFO/master/assets/api_key_visual.png" alt="API Key Instructions">

To put your API key into the program:
- Locate the api_key.env file in the ASTROINFO folder
- Open the file using your file editor
- Replace DEMO_KEY with your API key

NOTE: DEMO_KEY will work as an API key, but it only can be used 40 times per hour. However,
if you get your own API key, then you will be able to use it 1,000 times an hour.


## Usage Examples
ASTROINFO could be used for anything related to asteroids and/or smallbodies. For instance:
- Use AOS to evaluate the danger of a future close approach of an asteroid
- Use ASTROINFO to get the diameter of an asteroid in kilometers
- Use classes for your own code (remember to follow the license guidelines)

##  License
This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
