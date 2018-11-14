Environnement de travail MelonJS
=========================================

To run
--------
# clone it
git clone https://github.com/MorganCode/melonJS.git
---------
cd melonsJS

# Make it your own
rm -rf .git && git init && npm init

# Install dependencies
npm install

# Start development live-reload server
npm start

# Start play

Une fois le serveur en route tapper le liens suivant : http://localhost:5000/static/melonJs/ 

# Change mapTiled

Le jeu ce lance, pour mettre votre propre niveau allez dans le fichier /melonJs/data/map/ et changer le nom "area01".

// load a level
me.levelDirector.loadLevel("area01"); 


dans le fichier melonJs/js/screens/play.js  
