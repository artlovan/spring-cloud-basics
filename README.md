# Ribbon Client Load Balancer

Demo app to balance the load with @RibbonClient without service discovery.

1. Start first instance of ribbon-time-service on port 4444
2. Start second instance of ribbon-time-service on port 5555
3. Start an instance of ribbon-time-app
4. hit $: curl localhost:8080, hit again (observe port in the response msg)
5. Bring down all the instances
