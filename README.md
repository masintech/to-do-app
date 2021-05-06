# Run by docker
### Dev phase
`docker-compose up`
### Production phase using nginx
`docker build -t <tag-name> . `
`docker run -p yourport:3000 <tag-name>`

# Dependencies
### express
npm install express
### reload automatically
npm install nodemon
### security: avoid malicious code from html/js/css
npm install sanitize-html
  
  
user: learn  
passwd: javascript  