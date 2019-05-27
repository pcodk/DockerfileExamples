Dockerfile demo stuff
===

This project contains various dockerfile manifestes used as part of aPeytz & Co Docker masterclass curriculum.

The repository contains different Dockerfiles that can be built with

````docker build -t <TagName> -f <Dockerfile> .````

Nginx examples
---

```docker build -t pcodk/nginxtest -f Dockerfile.nginx .```

Then run the container with ```docker run -p8080:80 pcodk/nginxtest``` and open you browser on http://localhost:8080
 