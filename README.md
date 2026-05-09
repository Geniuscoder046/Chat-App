Snappy - Chat Application
Snappy is chat application build with the power of MERN Stack. You can find the tutorial here

login page
<img width="1871" height="899" alt="image" src="https://github.com/user-attachments/assets/5669a8b5-7c71-458d-abe5-920e0971d2ec" />

home page
<img width="1847" height="894" alt="image" src="https://github.com/user-attachments/assets/8aa47140-e36e-4352-b685-d709ac29142c" />

Installation Guide
Requirements
Nodejs
Mongodb
Both should be installed and make sure mongodb is running.

Installation
First Method
git clone https://github.com/koolkishan/chat-app-react-nodejs
cd chat-app-react-nodejs
Now rename env files from .env.example to .env

cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
Now install the dependencies

cd server
yarn
cd ..
cd public
yarn
We are almost done, Now just start the development server.

For Frontend.

cd public
yarn start
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.

cd server
yarn start
Done! Now open localhost:3000 in your browser.

Second Method
This method requires docker and docker-compose to be installed in your system.
Make sure you are in the root of your project and run the following command.
docker compose build --no-cache
after the build is complete run the containers using the following command

docker compose up
now open localhost:3000 in your browser.
