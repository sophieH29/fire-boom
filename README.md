# fire-boom
Progreesive Web App that was built with Firebase, Polymerfire and Polymer components for the demo during speaking at DevFest. 
Was built based onthis codelab: https://codelabs.developers.google.com/codelabs/polymer-firebase-pwa/

This web application is kind of public channel or just public notes, where people can communicate with each other, use emojis and likes posts.
- works offline
- has push notifications, but I sending message using post man for now
```
POST https://fcm.googleapis.com/fcm/send
Authorization: key=<YOUR_SERVER_KEY>, 
Content-Type: application/json


{
"to": "<USER_PUSH_TOKEN>",
 	"notification": {
 		"title": "Background Message Title",
 		"body": "Background message body",
 		"click_action": "https://fire-boom.firebaseapp.com/"
		"icon": "https://fire-boom.firebaseapp.com/images/boom1.png"
 	}
}
```

- Google authentication
- Real time Firebase database

Try and enjoy! :)
