# To-do-List


This is a basic todo list using Node,Express and stores list using arrays no database is used.
Install the dependencies by looking into pacakges.json file



If we need database like Mongodb
1.Install mongoose dependency.
2.Create a cluster in MongoDb.
3. Next add below 2 lines in app.js
    const mongoose=require("mongoose");
    mongoose.connect("Cluster link",{useUnifiedTopology:true,useNewUrlParser:true});

