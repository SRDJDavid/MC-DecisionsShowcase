# MC-DecisionsShowcase
This displays Decisions and how it may be applied in this survey that asks users about their information and mobile device. 

This was built in Decisions 6.9.2.

When you import the entire zip to your Decisions instance, it will create a root folder named "Mortgage Connect | SDavid Showcase". Here, you can navigate to Flows and find the Flow_mobileSurvey which is, and tagged, the main flow. 

Flow will ask the user their name, email, type of mobile device, and age. Validation and visibilty rules were used to confirm each entry was valid. 

Requirements and functionality pasted below. 

If their age is 21 or below and they have an Apple phone OR their age is 40 or above and they have an Android phone, ask them if they would like to participate in a research program.

If they select ‘Yes’ AND they are part of the ‘21 or below and Apple’ group, send them an email thanking them for joining the ‘Apple Research Program’.

If they select ‘Yes’ AND they are part of the ‘40 or above and Android’ group, send them an email thanking them for joining the ‘Android Research Program’.

For any other scenario, the flow will end with a form thanking them for participating in the survey.
