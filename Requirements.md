# COVID19
COVID19 Technology Platform

Phase 1 : COVID19 StageIII Tracker App
(Planned Release by 1st April,2020)

Requirements:
I> User Signup & Profile:
1. Ability for the users to download the mobile app(Android for now) and signup using their mobile phone number(2-step verification)
2. Profile: Signup user is mandated to update his/her profile(Full Name, Age, Gender, Existing Diseases, 2020 Travel history, COVID19 symptoms
3. Allow to access location and Radios of the Phone for sensing and location sharing purpose
4. Sign the consent form about sharing meta data of the user to help others. Remember, we wil keep personal data extremely private.

II> COVID19 Symptoms part of User profile
1. I do not have any symptoms/I have symptoms with travel history/I have symptoms without travel history
2. Use existing self assessment tests (https://covid.apollo247.com/info?id=1)
Note: The self assessment testcovers all questions. We can add features to make it more user friendly especially in sections where travel history is addressed. For example: We can add a pop-up map to indicate affected areas. This can be done at City/State or Country level
3. Address Community Spread: Identify areas like airports, markets etc. which are high risk and collect data as to when they last visited these places and include it in self assessment/touchpoints count

III> System to validate the vulnerability of the user based on profile and suggest
1. Users get alaerted based on touchpoints about vulnerabilities
2. Users can always update their COVID19 profile

IV> Continuous background sensing to nearby touchpoints of the users around
1. Touchpoints are validated based on Immediate/Near/Far regions of the other users around
2. Alert and warn the user based on touchpoints and the profile of the touchpoints
3. User can be asked to wash hands/see doctor/self quarantine etc
4. Users to update their COVID19 profile with the current status(A easy UX as this is the cruitial step)

V> Ability to trace and identify potential threats based on their profile and travel history(Google Maps data of last 14 days)
1. Alert users with valid info
2. Share local authorities about threats and zones (All this through cloud login for local authorities)

IV> Cloud design & architecture
1. Privacy first architecture
2. User, Role and permissions management
3. Loosly coupled architecture for extensibility 
4. Local authorities interface to monitor StageIII users and their vulnerabilities(Best UX with heatchart for easy tracing for authorities)
5. Interation with other open APIs for travel, disease, alert related data. validate https://api.covid19india.org/
