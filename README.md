Usage:
------

1. Start "discovery-server"
2. Start "config-server"
3. Start "config-client-app"
4. Open browser, request http://localhost:8080
5. Observe that configuration are loaded from "scf-config-repository" from "application.properties" and "config-client-app.properties"
6. Optional: Change for instance "config-client-app.properties", issue http request -> curl -d '{}' localhost:8080/refresh -v | json_pp, request http://localhost:8080
7. Once done, stop all instances
