**Design:
https://xd.adobe.com/spec/97a30b95-6c0a-4ea2-7a0a-7d20820e7488-e192/

This design is used in a business event/conference, where attendees submit a code. 

**UI Requirements:
1. Design the components in React-Native according to the designs 
2. The top message will live update participated event attendee numbers and code submission numbers
3. Input of the code will be validated with error handling

**App Requirements (please comment in the code to answer):
1. Traffic. Assume there will be around 3000 devices with 3000 codes submit every second for one event, and there would be around 100 events like this in a city. How you build this real-time system to support this?

2. Connection: Assume this will be in a crowd place without a stable connection. There will be delays and timeouts. And sometimes, the WiFi login may hijack the requests. How those scenarios would be handled. How do you handle these scenarios to keep the live update message work?

3. What kind of devops architecture you think needed for this? (please explain in the code comment or any chart file)

**Instructions: 
1. Fork this repo and code.
2. Submit back your github repo.
