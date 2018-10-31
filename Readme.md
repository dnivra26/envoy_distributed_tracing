## Distributed Tracing with Envoy service mesh & Jaeger  
![setup](https://raw.githubusercontent.com/dnivra26/envoy_distributed_tracing/master/distributed_tracing.png)


### Run:  
1. `docker-compose build`  
2. `docker-compose up`  
3. Hit http://localhost:8080 to generate some tracing   data  
4. Visit http://localhost:16686 in your browser

This is what the output should look like

![output](https://raw.githubusercontent.com/dnivra26/envoy_distributed_tracing/master/output.png)
