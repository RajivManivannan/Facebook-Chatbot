# Facebook-Chatbot  

Facebook Chatbot implementation in PHP.  

## Steps to set up localhost for chatbot.

1. Install AMPPS (Local PHP Web server + MySQL)  
2. To allow the tunnel request from facebook to localhost server, Install Ngrok  
3. Type the following command in terminal ./ngrok http 80  
4. Copy the forwarded https link from the terminal (https://xxxxx.ngrok.io)   
5. To change port number ./ngrok http PORT_NUMBER  
6. To check https traffic use the following url:  localhost:4040/inspect/http  
7. Download the following SSL cetrificate from https://curl.haxx.se/ca/cacert.pem and configure in localhost  
