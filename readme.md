# Showtime

### 1. get dependencies

    npm install

### 2. run static server

    npm start

### 3. view in browser

    http://localhost:8080

# Plan

* Intro
* The problem
  * We live in a mobile world now
  * Modules
    * Fig: dependency tree
  * Bundling and lazy loading
  * Lazy vs eager: the two extremes
  * RTT vs parsing
  * The theoretical solution
* ES6 Modules
  * New syntax
  * Static analysis
  * Code and demo
  * Status
* HTTP/2
  * Lots of details we don't need to worry about
  * Pushing stuff!
  * Combine with static analysis
  * Code and demo
  * Overly eager: wasted bandwith
* Service Worker
  * Theory: Proxy server on the client
  * Install, fetch and cache
  * Arbitrary code in fetch
* Bloom Filter
  * The remaining problem
  * Letting the server know what we have
  * Theory
  * Math
  * Client code
  * Server code
* Putting it all together
* Conclusion