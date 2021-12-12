##Use this skill to control your Phillips Hue lights.

#### Setup :

- Configure Alice to your PhilipsHue hub. Alice will run you through these steps so please 
listen to her requests when you install the skill.

#### Usage :

Some examples of what to say :

- "turn the office lights off". *You need a room named Office in your Phue configuration*
- "turn the office lights on". *You need a room named Office in your Phue configuration*
- "set to 50% the lights in the kitchen". *You need a room named Kitchen in your Phue configuration*
- "toggle light in the office". *You need a room named Office in your Phue configuration*
- "change the lights in the bedroom to going bed". *You need a room named Bedroom and a scene named Going bed in your Phue configuration*

#### Settings

- matchLightWithDaytime: Alice will match the light scene with the part of the day. You need 6 scenes configured for your house:
  - Early morning
  - Morning
  - Afternoon
  - Evening
  - Night
  - Sleeping
- goodNightTurnsOffEverything: If enabled, saying good night to Alice will turn off all your lights
- goingOutTurnsOffEverything: If enabled, telling Alice that you are going out will turn off all your lights after 5 minutes

#### Note: 

If you have another skill installed that also controls lights, such as the Home Assistant skill. You may find 
that skill will take dominance over your Phillips hue lights. In that case, try using utterances where 
"hue" or "philips hue" is in the utterance. Often just before the word light.

Example:  

- "turn the office hue lights off"
- "turn the office phillips hue lights on"
- "set to 50% the Hue lights in the kitchen"
- "toggle Hue light in the office"
- "change the Philips hue lights in the bedroom to going bed"
