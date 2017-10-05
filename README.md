# fn-time
Sample project for fn container serverless platform. 

Note : You can install fn service via docker. Pull the image and run as below;
```
docker pull fnproject/functions

docker container run fnproject/functions
```

And then we can create first function;

1. Create new function in any language. File name should be **func.*** for example -> func.go
2. Typing ``` fn init ``` after this command you can see that func.yaml is created.
3. Run your function as follow -> ``` fn run ```
  FN, build the your function to docker images and then run immediately.
4. After above processes you can confirm that your images created via this command ``` docker images | head -5 ```
  You can run your function via docker instead of FN.
  
Our example is returning current time when called.

You can test it via my docker image, pull it and run it! ;

``` docker pull aakkus/time:0.0.2 ```
