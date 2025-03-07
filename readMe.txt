Expree routing parameters

app.get("/news/:topic", function(req,res){
    console.log(req.params.topic)
});

// localhost:3000/news/tech 
// tech (topic) will be logged on console