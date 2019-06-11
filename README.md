# Archetype_identification
Lookng at all the post made by the user in twitter, we in this project are intrested to find the archetype of the user.

<h2>Example</h2>
 from archtype_user_identification.classify_user import classify_user</br>
 classification = classify_user(list_group=['book','music','tech','travel'], API_KEYS, API_SECRET_KEY, ACCESS_TOKEN,   ACCESS_TOKEN_SECRET) #API keys are from twitter api @ https://developer.twitter.com/apps</br>
 print(classification.classify('elonmusk')) #output -> tech</br>
 print(classification.classify('RollingStone')) #output -> music</br>

<h2>Steps</h2>
1)Clone the project</br>
2)Install the requirements</br>
3)Use as given in example
