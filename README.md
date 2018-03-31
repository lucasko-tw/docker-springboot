

```
 docker rm -f boot && docker run --name boot -p 8080:8080 -v $PWD/your-springboot-project:/opt -v ~/.m2:/root/.m2  -it lucasko/springboot 
```
