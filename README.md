playing-with-redis-mongo-node.js

Repository created specifically for learning redis caching.

##

[![Join the chat](https://img.shields.io/badge/gitter-join%20chat%20%E2%86%92-brightgreen.svg)](https://gitter.im/divyanshu001)
[![Contact me on Codementor](https://cdn.codementor.io/badges/contact_me_github.svg)](https://www.codementor.io/divyanshurawat?utm_source=github&utm_medium=button&utm_term=divyanshurawat&utm_campaign=github)
[![Twitter URL](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/r46956)
[![DUB](https://img.shields.io/dub/l/vibe-d.svg?style=flat)](#)

[![Divyanshu](https://img.shields.io/badge/divyanshu-owner-brightgreen.svg?style=flat)](http://www.divyanshurawat.in)
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/divyanshu-rawat)
[![NPM](https://img.shields.io/badge/npm-v3.10.10-blue.svg)](https://www.npmjs.com/package/npm)

##

### Description 

* let's have some cached data by leveraging redis-client.

##

### Installation Instructions

* Open a command prompt in the project's root directory.

* Cd into that root folder you just cloned locally.

* Open terminal in the current folder and to install all dependencies type 

```javascript
   npm install 
```

* This installs the dependencies as defined in the package.json file.


* Run 2 seperate servers dog_server.js and cat_server.js by typing 

```javascript
  npm dog_server.js 
```

```javascript
  npm cat_server.js
```

* once done with running cat and dog server respectively run pet_server.js which will in turn communicate with other running servers and fetch data in async manner by levaraging node async module and cached it with redis.

* Command to run pet_server is node pet_server.js.

```javascript
   npm start 
```

* This will run the server in the localhost.



NOTE : Don't forget to run redis client and mongoDB on seperate host.

##


### Contributing

1. Create your **_branch_**: `git checkout -b my-new-feature`

2. **_Commit_** your changes: `git commit -m 'Add some feature'`

3. **_Push_** to the branch: `git push origin my-new-feature`

4. Send a **Pull Request**

5. **_Enjoy!_**

##

In total you will have to run 5 servers which will look like below-mentioned image.

![alt tag](https://github.com/divyanshu-rawat/playing-with-redis-mongo-node.js/blob/master/snaps/Screen%20Shot%202017-09-22%20at%209.17.04%20PM.png)

