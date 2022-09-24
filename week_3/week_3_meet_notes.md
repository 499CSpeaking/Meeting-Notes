# WEEK 3 MEETING NOTES

## COMMUNICATION

- Our meeting times will usually be 4-5pm on Friday.
- Nazim is planning to make a discord server so that He, Justing (the in-house developer), and all 3 groups can communicate. 
- Justin (and other developers at Kukarella) will be able to communicate with us at least once a week. If they are busy, we can leave chat messages for them.
- Our meetings will usually be online (via Discord) but we can do in-person meetings around once a month.
- Nazim will try to be avaliable for communication for the entire duration of the project.

## PROJECT SPECIFICATION

### project functionality
- The program will take in text as an input, and output a video.
- The output video is an actual video file that can be used anywhere.
- User can choose an default avatar, or upload their own.
- Talking avatar might be an add-on/plugin/similar as it must be usable anywhere, not just on Kukarella's website.
- *I'm a little confused about these last 2 points, is the add-on a menu that takes in text and generates a video file?* 
- We have full freedom over how we create a talking avatar (using a 3D avatar, using AI to animate images, etc.)
- We will have access to Kukarella's voices +  existing speech APIs.
- We will mostly be working on a backend, only using a small frontend for testing/showcases.
- Nazim describes the output to be a GIF (not sure if he means specifically a GIF or any kind of video.)
- We should be able to upload multiple images at a time.(?)
- If we need 3D models, we can use Kukarella's financial resources to obtain them.
### requirements for success
- Currently, our only functionality-related criteria is that the service works fast.
### agile
- Nazim wishes for us to deliver in 2-week iterations. 
- We will discuss important milestones next week, but christmas time is an important milestone for Nazim.


## TECHNICAL DETAILS

### codebases
- Our project's repository and Kukarella's codebase will be kept separate.
- It is suggested we use Typescript, but not necessary.
- In order to maintain formatting consistency with Kukarella, we can use the *prettier* formatter.
- Kukarella's software is hosted on AWS Elastic Beanstalk.

### api integration
- Kukarella's text-to-speech API is mostly internal, and doesn't have any obvious public endpoints
- However, Justin knows of an endpoint which we can potentially use. It involves sending an API key and recieving a URL to the text-to-speech API endpoint.

# GOALS FOR NEXT WEEK
- **important**: Next Friday is a holiday, so we must meet on Thursday or another day.
- Research methods and approaches to animating an image to speak. 
- Possibly see if we are allowed to work together with the other two teams on some aspects of the project. Nazim is content with this, but what about the professor?