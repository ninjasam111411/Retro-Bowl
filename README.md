# Retro-Bowl
Retro Bowl is a Retro Football game with...
<br><br>
-Multiple save files, 
<br>
-Kickoffs 
<br>
-and more. 
<br><br>
You cant play this if you download it so host to an webpage (vercel, netlify, etc) or download it at this other <a href="https://github.com/CAPPRIME/Retro-Bowl-Download">repository</a><br>
Have fun <br>
[![Deploy with Vercel](https://binbashbanana.github.io/deploy-buttons/buttons/remade/vercel.svg)](https://vercel.com/new/clone?repositoryurl=https://github.com/CAPPRIME/Retro-Bowl)
<br>
Note: I DID NOT MAKE THIS GAME


game link at https://retro-bowl-wine.vercel.app/

to get more coaching credits open the console and run

let key = "RetroBowl.0.savedata.ini";
let save = localStorage.getItem(key);
if (save) {
  save = save.replace(/coach_credit="?\d+"?/g, 'coach_credit="999"');
  localStorage.setItem(key, save);
  console.log("Coaching credits changed to 999!");
}


relpace coach_credit="999"' with however many credits you want


after all of that close and repoen the tab with the game to have it update with all of the credits
