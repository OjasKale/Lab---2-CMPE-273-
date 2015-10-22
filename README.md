# Lab---2-CMPE-273-
POST method that takes JSON request and returns JSON response.


The process to run this program is,
first set the GOPATH if you havent set,
then normally run the proram
as follows:

Ojass-MacBook-Pro:src ojaskale$ go run post_demo1.go

Ojass-MacBook-Pro:~ ojaskale$ curl -H "Content-Type: application/json" -d '{"name":"Ojas"}' http://localhost:3000/hello
{"greeting":"Hello, Ojas!"}

Ojass-MacBook-Pro:~ ojaskale$ 
