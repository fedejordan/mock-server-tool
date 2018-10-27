# mock-server-tool
Simple script that creates a Node.js REST server using JSON files as mocked responses

<img src="example.gif"
     alt="Example of use"
     width='75%'
     height='75%'
     style="float: left" />
     
## Requirements:
- npm 5.5.1 or superior

## Usage
1. Run the following command: `node create-mock-server.js`
2. Follow the instructions to create your mocked endpoints
3. Once the local server is running, go to your created project folder and modify the JSON files to your desired resposnes.
4. Test the server with cURL or Postman. 

## Future improvements:
- Validate inputs (empty strings, type of data, etc)
- Constraint to REST methods 
- Export a Postman specification
- Export cURLs
- Refactor project in submodules, now it's just a huge 503 lines file :neutral_face:

Follow me on tw: [@FedeJordan90](https://twitter.com/FedeJordan90)
Email: fedejordan99@gmail.com

Thanks!
     
