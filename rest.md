### Rest architecture constraints

- uniform interface : resource based/manipulation through representations

- stateless : no client state/info caching on server side. each request is independent.

- cacheable : server responses can be cached on client side.

- client server : separation of conncerns/client app / server can be modified independently

- layered system : possibly client can be connected to end server via intermediate servers(load balancers etc)

- code on demand
