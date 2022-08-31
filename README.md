# mqtt-chat-web-demo
MQTT-CHAT cloud web  is an chat library that provides full chat functionality and can be integrated  quickly into any web application.
<br>It allows you to integrate a complete messenger in your application through a few lines of code. Even a beginner in web development can integrate it easily. 
<br>MQTT-CHAT cloud web is a complete messaging application similar to those used by facebook, linkedIn etc...
<br>Below some screenshots of the demo application hosted in this github repository.
<img src="https://github.com/medaboub/mqtt-chat-web-demo/blob/main/screenshot_docked.png"><br><br>
<img src="https://github.com/medaboub/mqtt-chat-web-demo/blob/main/screenshot_docked03.png">
<img src="https://github.com/medaboub/mqtt-chat-web-demo/blob/main/screenshot_docked05.png">
## Integration
Add MQTTchat script to the header of your page just after JQuery Script.
```html
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script> 
 <script src="https://cluster1.telifoun.com/webapi/ar/mqttchat.js?appid=mqttchat-87226030&uf=0"></script>
```

### Docked Layout
In the body of your page, where you want to display MQTT chat,  add #mqttchat div to show docked layouts.
```html
 <div id="mqttchat"   
          data-layout="docked"   
          class="mqttchat-lite" 
          data-user-name="user"
          data-user-surname="126"
          data-user-link=""
          data-user-avatar=""          
          data-user-id="126"
          data-user-gender="0"          
     ></div>
```

### Embedded Layout
In the body of your page, where you want to display MQTT chat,  add #mqttchat div to show embedded layouts.
```html
<div id="mqttchat"   
          data-layout="embedded"   
          class="mqttchat-lite" 
          data-user-name="user"
          data-user-surname="1"
          data-user-link=""
          data-user-avatar=""          
          data-user-id="21"
          data-user-gender="0"  
          data-width="950"
          data-height="650"        
     ></div>
```

## Library features
- Real-time Text Messaging
- One-on-one Chat
- Photos Sharing
- Capture photos from Webcam
- Stickers & Emojis
- Block Users
- Friends feature for dating or social networks websites
- Voice Notes
- Audio & Video Calls using WebRTC
- Typing Indicators
- Read Receipts
- Languages : ar, fr, en
- Storage Space : up to 2Go
- Data Retention : up to 30 days
- WEB Push Notifications
- Presence & messages webhooks.
<br><br>And much more ...

## Documentation
__For more informations please read the complete <a href="https://doc.mqtt-chat.com/mqttchat-cloud-web/integration">MQTT-CHAT web documentation</a>.__

