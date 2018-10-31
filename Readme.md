## Distributed Tracing with Envoy service mesh & Jaeger  
![setup](https://raw.githubusercontent.com/dnivra26/envoy_distributed_tracing/master/distributed_tracing.png)


Run:  
`docker-compose build`  
`docker-compose up`  
Hit http://localhost:8080 to generate some tracing   data
Visit http://localhost:16686 in your browser

This is what the output should look like

![output](https://raw.githubusercontent.com/dnivra26/envoy_distributed_tracing/master/output.png)
