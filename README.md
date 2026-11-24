# Layla-AI-Lovense-Integration
A Layla agent and lorebook to allow lovense toys to be controlled fully independently by an AI chat within the app

The agent JSON can be imported using the Layla Agents mini app. The lorebook JSON needs to be imported using the Layla References mini app. 

An important note about this project, I'm not a programmer so code has been made with AI help and may not be the best or most efficient code. I've got to a point where the code and controls by the AI model within Layla appears to work without issue. 

The context required within Layla to use this project as is has to be 6k tokens or higher and even 6k is a very very tight tolerance. This is specifically for the toys I have, I've not added all lovense toys to the code but I do plan to once I know some more about how everything works and the lorebook may have to become multiple lorebooks (ie one for each toy) which could cut the required context tokens significantly; especially if you're only wanting to use one toy. 

My current testing has been done on the latest Layla app (7.7.0 as of writing this readme but will always be the latest version so check what this is) which is running on a Redmagic 11 Golden Saga phone with 24gb RAM and 1tb storage. Any model should work but I have only tested with Gemma 4 12b Q4_K_M (abliterated/heretic so it doesn't refuse ERP spicy prompts). 12b model quantized so I had the RAM overhead (context set to 8k or more, to test and a faster response than larger models). 

Future plans, I'll look at making individual lorebooks that could work a lot better for less memory and smaller context can be used which is especially useful for anyone using a single toy. I also plan on getting a working template so I could make lorebooks for other toys I don't own without needing to test myself and have a high degree of confidence it'll just work (this could also potentially be a Layla mini app that looks at what's connected then makes a custom lorebook, this is way above my current skill level). There is also potential to tweak the agent code and make things a lot more streamlined, not sure if it's possible yet as I was just happy to have a working system and don't want to break it before I'd tested it. 

