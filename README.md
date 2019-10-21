# Http2--Server-push

Nodejs Version is v12.9.0 for this application
### Requirements: 

-[x] Node.js >= 8.4.0

openssl for creating self signed certificates:

-`openssl req -x509 -newkey rsa:2048 -nodes -sha256 -subj '/CN=localhost' -keyout key.pem -out cert.pem`

### Run

-`npm start` 

or 

-`npm index.js`

Open: https://localhost:3000 for https/1.1 protocol
and 
Open: https://localhost:3000 for https/2 serverpush
