# boilerPlateJS


const express = require("express");
const app = express();

app.get('/',function(req,res){
   res.send("server is running"); 
})

app.listen(3000,function(){
    console.log("listening at server 3000");
})
