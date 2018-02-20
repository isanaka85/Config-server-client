# Config-server-client
Spring Cloud Config Server with Git Integration


To reflect the new value, we need to refresh the configuration by hitting http://localhost:9999/refresh endpoint using POST method from any of the REST client(postman).

Once you have successfully refreshed the config client service, the new value should be reflected in the service response. This is because @RefreshScope annotation the Rest Controller that we have exposed.


