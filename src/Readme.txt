http://localhost:8080/
http://localhost:8080/posts/search/findByAuthor_Lastname?lastname=Holderness
curl -i -X POST -H "Content-Type:application/json" -d '{"title" : "This is the title", "body" : "This is the body."}' http://localhost:8080/api/v1/posts