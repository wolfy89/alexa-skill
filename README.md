# alexa-skill

This is a description of a very basic customed skill for Alexa and what you have to do to make your own. 
Mine is very simple, when I tell "Alexa c'est une bonne situation ça scribe ?", Alexa tells me the Otis monologue from the movie "Asterix Mission Cléopâtre" 

I) Create an account on https://developer.amazon.com and log in 

II) Follow the link : https://developer.amazon.com/alexa/console/ask#/skill/create/

III) Click on the blue button "create skill"

IV) Enter your skill name (this name will be the name on the store), your language, choose the "custom" model and a host (I chose node.js) and click on "create skill" 

V) The "Build" part 
1) Select "invocation" and enter a "skill invocation name" and click on "save model" : the name you gave is the name you will tell to Alexa to launch your skill. For example, mine is "Otis scribe" and to launch it I say "Alexa, open Otis scribe"

2) Select "intent" and click on "add intent" : mine is AsterixIntent. don't worry, the user will not have to say this intent. Then click on "create custom intent"

3) you will have to create "sample utterances". Basically this is the sentence the user must pronounce to trigger an answer from Alexa. for example mine are "Quelle est la réplique du scribe dans astérix mission cléopatre", "Quelle est la réplique du Scribe", "Quelle est la réplique d'Otis", "C'est une bonne situation Scribe", "C'est une bonne situation ça Scribe"...
Then click on "save model" and "Build Model". (You can also create an intern slot but I didn't try it for my first skill so I couldn't help for this part. but there is a lot of tutorials on the internet)

VI) The "Code" part 
See my code and my comments to see what to change to make your own. I changed the index.js and the package.json. When everything is ok click on "deploy" 

VII) The "Test" part. 
Try to type (or say) "alexa, open + your_skill_invocation_name" and alexa will launch. Then say or write one of your sample utterances and here we go ! 

VIII) the "Distribution" part
It is where you have to enter a description of your skill and upload a logo. Nothing complicated here.  

IX) The "Certification" part 
1) click on "run" it is the part where Amazon will see if everything is ok with your skill (no code error) 

2) when everything is ok, click on "submission" and on "submit for review". Then all you have to do is wait for Amazon to validate your submission (it takes 15 days...) 

Have fun ! 
