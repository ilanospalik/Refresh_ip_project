# Refresh_ip_project
1. I Created a private repo on github.
2. I took the app from the task and deploy it on 3 flask app containers that prints the local IP to the browser (on HTTP - port 80) 
3. Created a load balancer based on a docker nginx image exposed on port 9090.
4. Create a docker compose that runs the 3 flask instances of the app + nginx loadbalancer + redis database.
5. CALL TO ACTION - Open browser and check http://localhost:9090, verify you see different IP each refresh.
6. i pushed my project to the private repo on github
