# URL Shortener Service
By Bhawani Prasad Mishra

[Instructions](#instruction)

API to create short urls using Node, Express and MongoDB

commands to execute:

1- npm install    # To install required node modules
2- npm start      # To run the application

Note: A rest API client is required to run url changer api.
It is recommended to use visual studio code along with Rest Client extension - https://marketplace.visualstudio.com/items?itemName=humao.rest-client

## Instruction:
### Setting URL
After executing above 2 commands, open "api.http" file inside "requests" directory.
Inside "longUrl" object, paste your url that has to be shortened and click "Send Request" at the top. (Send Request will only be visible if you are using Rest Client for VS code)

### Reading generated shortened URL
This will generate a response from rest API with fields containing "longUrl" and "shortUrl".
The "longUrl" is the inserted url, the "shortUrl" is the shortened url, and our required result.

Enhancement: A UI version could also be developed if CORS could be solved without using proxy.

Image with instructions attached![Annotation 2021-04-24 153544](https://user-images.githubusercontent.com/38910619/115955276-25ad2d00-a513-11eb-9bbe-e3dc232b7ec4.jpg)
