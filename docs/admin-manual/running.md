ShellHub provides a docker-compose file that will set up and run
everything for you on a single host.

!!! info ""
	Running ShellHub in a multi-host environment with Kubernetes or Docker Swarm is beyond the scope of this guide.

To run ShellHub you can just simply run the up command with docker-compose wrapper inside
of ShellHub project dir:

```
./bin/docker-compose up -d
```

!!! warning "Be patient, it can take up to 10 minutes for the first time"

When ShellHub server is up and running, you access the Web UI on [http://localhost](http://localhost).
