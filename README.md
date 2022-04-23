#level 2 Encryption
Caesar cipher
simple encrytion algorithm

#level 3 Add Environment Vars
npm i dotenv
protect secrets like api from seeing in github

#level 4 Hashing Passwords
npm i md5
can hack it with dictionary hashtable
same string generate same hash, easier to crack when multiple people use same password

#level 5 Salting and Hashing Passwords with bcrypt
bcrypt is a level up from md5
salt: random number
salt rounds: multiple hash use same salt

#level 6 Cookies and Sessions
use passport.js to add Cookies and Sessions

#level 7 OAuth & Sign in with Google
use OAuth to sign in with third-parties like facebook, google..
avoid the situation to save users' pwd by yourself, lean on the save and encription of google, safer
