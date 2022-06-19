# Login with google
---------------------------------------------------
# Google stuffs

go to https://console.cloud.google.com/apis/credentials

![image](https://user-images.githubusercontent.com/60959655/174465484-e717824a-8a66-409a-80dc-e2aba458a48c.png)

Choose "Web Application" in Application type and give your app name in Name.

Add "http://localhost:3000" in Authorized JavaScript origins.

Add "http://localhost:3000" in Authorized redirect URIs and save them.

Copy client_id, you will need it later.

go to https://console.cloud.google.com/apis/credentials/consent.

select the app name you created in credentials.

![image](https://user-images.githubusercontent.com/60959655/174465664-00611878-3b2f-4960-91fd-32514703d8df.png)

make User Type "External"

add app name, support email in App information section and email address in Developer contact information section.

add test users in Test users section.

You are all done with google stuffs. 

# Backend
Go through sample user.model provided above.

Make a route accordingly.

# Frontend
make .env file in your root dir and add client_id there.

![image](https://user-images.githubusercontent.com/60959655/174465965-0744c286-943a-404c-b503-d100ada493ac.png)

npm install axios gapi-script react-google-login

Go through sample LoginGoogle.js and Login.js.

Ta-Da! You are all done.✔
Don't forget to give me a ⭐. Peace 🍀







