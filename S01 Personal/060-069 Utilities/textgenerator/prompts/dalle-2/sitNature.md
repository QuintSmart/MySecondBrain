---
tags: 
PromptInfo:
 promptId: sitNature
 name: 🖼️ Generate a Nature photo
 description: Photographs in the dataset with these captions tend to showcase animals/nature in extraordinary positions and situations, works similarly to “Award-Winning” but is only for nature. This will also make animals/nature look more real and accurate.
 author: Prompt Engineering Guide
 tags: photo, dalle-2, situational
 version: 0.0.1
config:
 append:
  bodyParams: false
  reqParams: true
 context: "prompt"
 output: '`\n![](${requestResults.data[0].url})`'
bodyParams:
 n: 1
 size: "1024x1024"
reqParams:
 url: "https://api.openai.com/v1/images/generations"
date_created: Tuesday, January 31st 2023, 3:24:37 pm
date_modified: Thursday, May 18th 2023, 6:15:55 pm
---
# sitNature
{{selection}}, Nature Photography