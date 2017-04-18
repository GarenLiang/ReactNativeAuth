# ReactNativeAuth

* React Native Auth Project with Firebase,Google Cloud,Twilio
* Create a twilio.js file in functions folder with accountSid and authToken
```javascript
const twilio = require('twilio');

const accountSid = '';
const authToken = '';

module.exports = new twilio.Twilio(accountSid, authToken);
```
