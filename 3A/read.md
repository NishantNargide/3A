npm init -y
npm install express --save
//terminal//

//create file server.js//
var express = require("express");

var app = express();

app.use(express.static('public'));



var server = app.listen(2001, function(){
    var port = server.address().port;
    console.log("Server started at http://localhost:%s", port);
});

//create new folder in current folder name it public& add //
index.html........


//run in terminal// 
node server.js

