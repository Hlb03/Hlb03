# Personal profile of software engineering skills

⬜ Optional, 🟦 Required for all, 🟨 Required for js, 🟩 Learned, 🟥 Declined

## Fundamental concepts

| Syntax               | Statements            | Functions             | Data structures     | Process & style      |
|----------------------|-----------------------|-----------------------|---------------------|----------------------|
| 🟩 value             | 🟩 if                 | 🟩 recursion          | 🟩 array            | 🟩 refactoring       |
| 🟩 identifier        | 🟩 loops              | 🟩 function           | 🟩 instance         | 🟩 code review       |
| 🟩 variable          | 🟦 assignment         | 🟩 return             | 🟩 object           | 🟩 antipatterns      |
| 🟩 constant          | 🟨 prototype          | 🟩 signature          | 🟩 collection       | 🟩 paradigm          |
| 🟩 scalar            | 🟩 class              | 🟩 argument           | 🟩 hash table       | 🟩 algorithm         |
| 🟩 literal           | 🟩 while              | 🟩 parameter          | 🟩 linked list      | 🟦 magic numbers     |
| 🟩 expression        | 🟩 do..while          | 🟦 pure function      | 🟩 queue            | 🟩 hardcode          |
| 🟩 heap              | 🟩 for                | 🟩 lambda             | 🟩 stack            | 🟩 complexity        |
| 🟩 type              | 🟨 for..in            | 🟦 side effects       | 🟩 deque            | 🟩 decomposition     |
| 🟩 primitive types   | 🟨 for..of            | 🟦 closure            | 🟩 serialization    | 🟩 spaghetti         |
| 🟩 reference         | 🟨 for await          | 🟦 partial            | 🟦 mixin, extend    | ⬜️ silver bullet     |
| 🟩 flag              | 🟩 throw              | ⬜️ curry              | 🟩 iterator         | ⬜️ not invented here |
| 🟩 lexical scope     | 🟩 try..catch         | 🟦 chaining           | 🟩 generics         | 🟩 dead code         |
| 🟩 code block        | 🟩 equality operators | 🟦 higher order       | 🟩 Map              | 🟩 unreachable code  |
| 🟩 Object            | 🟩 logical operators  | 🟦 callback           | 🟩 Set              | 🟩 duplicate code    |
| 🟩 this              | 🟩 bitwise operators  | 🟦 listener           | ⬜️ weak collections | 🟩 exception         |
| 🟨 arrow function    | 🟩 break, continue    | ⬜️ pipe               | 🟩 Proxy            | 🟩 return early      |
| 🟨 generator         | 🟩 switch             | ⬜ compose            | ⬜️ Symbol           | 🟩 unittest          |
| 🟨 async function    | 🟩 new Error          | ⬜️ memoize            | 🟩 string parsing   | ⬜️ prettier          |
| 🟨 call, bind, apply |                       | 🟩 factory            | 🟨 timers           | 🟩 git                |
| 🟩 Array             |                       | 🟩 pool               | 🟨 EventEmitter     | 🟩 github             |
| 🟩 instanceof        |                       | 🟦 wrapper            | 🟩 RegExp           | 🟩 node.js            |
| 🟨 ...spread         |                       | 🟩 default parameters | 🟨 global           | 🟨 npm                |
| 🟨 ...rest           |                       |                       | 🟨 undefined        |                        |
| 🟨 typeof            |                       |                       | 🟩 null             |                       |

## Multi-paradigm programming

| Theory                         | OOP basics            | Abstractions         | Patterns                 |
|--------------------------------|-----------------------|----------------------|--------------------------|
| 🟩 Procedural programming      | 🟩 constructor        | ⬜ struct, record    | 🟩 Singleton             |
| 🟩 Imperative programming      | 🟩 new                | 🟩 Mutable state     | 🟩 Factory method        |
| 🟦 Structured programming      | 🟩 Static method      | 🟩 Immutable state   | 🟩 Abstract factory      |
| 🟦 Non-structured programming  | 🟩 Method             | 🟩 Enum              | 🟩 Builder               |
| 🟩 Functional programming      | 🟦 Async method       | 🟩 Linked list       | 🟩 Proxy                 |
| 🟦 Prototype-based programming | 🟩 Getters, Setters   | 🟦 Doubly list       | 🟩 Adapter               |
| 🟩 Object-oriented programming | 🟩 Public fields      | 🟦 Unrolled list     | 🟩 Decorator             |
| ⬜ Object-based programming    | 🟩 Private fields     | 🟦 Circular list     |                          |
| 🟩 Generic programming         | 🟩 Field declarations | 🟩 Trees             |                          |
| 🟩 Concurrent computing        | 🟩 Inheritance        | 🟩 Graphs            |                          |
| 🟦 Asyncronous programming     | 🟩 Parent class       | 🟦 Functor           |                          |
| 🟩 Parallel programming        | 🟩 Polymorphism       | 🟦 Functional object |                          |
| 🟦 Reactive programming        | 🟩 Abstract class     | ⬜ Monad             |                          |
| ⬜ FRP (Functional-reactive)   | 🟩 Interface          | 🟩 Generator         |                          |
| 🟦 Automata-based programming  | 🟩 Encapsulation      | 🟩 Iterator          |                          |
| 🟦 Domain-specific languages   | 🟩 Hidden class       | 🟦 Async Iterator    |                          |
| 🟦 Multi-paradigm programming  | ⬜ Object form        |                      |                          |
| ⬜ Metaprogramming             | 🟩 instance           |                      |                          |
| ⬜ Actor model                 | ⬜ Introspection      |                      |                          |
|                                | 🟩 Reflection         |                      |                          |

## Java basics

| Collections           | Multithreading               | Network          | Technique        | Problems             |
|----------------------|------------------------------|-------------------|------------------|----------------------|
|    List              | 🟩 Semaphores               | 🟦 TCP/SSL        | 🟩 Testing       | 🟦 Resource leaks    |
| 🟩 Arrays List       | 🟩 Critical sections        | 🟦 UDP            | ⬜ CI/CD         | 🟦 Blocking code     |
| 🟩 Linked List       | 🟩 Synchronized blocks      | 🟦 TLS            | 🟦 Readable      | 🟦 Data race         |
| 🟩 Vector            | 🟩 Locks                    | 🟦 Websocket      | 🟦 Writable      | 🟦 Graceful Shutdown |
|   Queue              | 🟩 Barriers                  | ⬜ SSE            | 🟦 Transform     | 🟩 Dependencies      |
| 🟩 PriorityQueue     |                              | ⬜ HTTP/3 (QUIC)  | ⬜ back pressure |                      |
|   Deque              |                              | ⬜ Long polling   | 🟩 Buffer        |                      |
| 🟩 ArrayDeque        |                             | 🟩 REST           | 🟩 Console       |                      |
|   Set                |                              | 🟦 RPC            | 🟦 Inspector     |                      |
| 🟩 HashSet           |                             | 🟦 Routing        | 🟦 Reliability   |                      |
| 🟩 LinkedHasSet      |                             | 🟦 IP sticky      | 🟦 Quality       |                      |
|   Sorted Set         |                              | 🟦 DoS            | 🟦 Availability  |                      |
| 🟩 TreeSet           |                             | 🟩 DDoS           | 🟦 Flexibility   |                      |
|   Map                |                              | 🟩 XSS            |                  |                      |
| 🟩 HashMap           |                             | 🟦 Path traversal |                  |                      |
| 🟩 LinkedHashMap     |                             | 🟩 CSRF           |                  |                      |
| 🟩 HashTable         |                             | 🟦 DNS            |                  |                      |
| 🟩 TreeMap           |                             |                   |                  |                      |
|                      |                              |                   |                  |                      |

## Technique skills

| Spring               | Data access                  | Java EE           | Other            | 
|----------------------|------------------------------|-------------------|------------------|
| 🟩 Spring Boot      | 🟩 Hibernate                 | 🟩 Servlets      | 🟩 Unit Testing  |
| 🟩 Spring Data      | 🟩 JDBC                      | 🟩 Filters       | 🟩 Mockito       |
| 🟩 Spring Secutiry  |                              |                   | 🟩 MySQL         | 
|                     |                               |                   | 🟩 Themeleaf    |
|                      |                              |                   | 🟩 JSP (JSTL)    |
|                      |                              |                   | 🟩 Maven


--------------------------------------------------------- END ---------------------------------------------------------
## Asynchronous programming

| Async contracts        | JavaScript & Node.js specific  | Theory              | Techniques               |
|------------------------|--------------------------------|---------------------|--------------------------|
| 🟦 Callback-last       | 🟦 Timers                      | 🟦 Event Loop       | ⬜ async.js library      |
| 🟦 Error-first         | 🟦 setImmediate                | 🟦 Async error      | ⬜ Async composition     |
| 🟦 Promise             | 🟦 nextTick                    | 🟦 try..catch       | ⬜ Rx.js                 |
| 🟦 Async function      | ⬜ AbortController             | 🟦 Non-blocking     | 🟦 Sequential async      |
| 🟦 await               | 🟦 Promise unhandled rejection | 🟦 Async I/O        | 🟦 Parallel async        |
| 🟦 Generator           | 🟦 Promise double resolve      | 🟦 Pattern Reactor  | 🟦 Promise.all           |
| 🟦 Async Generator     | 🟦 child_process               | ⬜ CAS operations   | 🟦 Promise.allSettled    |
| 🟦 Async Iterator      | 🟦 worker_threads              | ⬜ epoll            | 🟦 Promise.race          |
| 🟦 Thenable            | 🟦 Atomics                     | ⬜ kqueue           | 🟦 Promise.any           |
| 🟦 EventEmitter        | 🟦 Blockeing operations        | ⬜ Completion ports | ⬜ Web Locks API         |
| ⬜ Cancelable callback | 🟦 Non-blocking loop for Array | ⬜ Event ports      | ⬜ Async Pool            |
| ⬜ Cancelable Promise  | ⬜ High resolution clock       | 🟦 libuv            | ⬜ Thread Pool           |
| 🟦 Asynchronous Queue  | 🟦 Callback hell               | 🟦 Race conditions  | 🟦 callbackify           |
| ⬜ Future              | 🟦 Promise hell                | 🟦 Dead locks       | 🟦 promisify             |
| ⬜ Deferred            |                                | 🟦 Live locks       | ⬜ IPC                   |
| 🟦 Observer            |                                | ⬜ Actor Model      | ⬜ Channel API           |
| ⬜ Async Collector     |                                |                     | ⬜ Revealing Constructor |
| ⬜ Coroutine           |                                |                     |                          |
| ⬜ Goroutine           |                                |                     |                          |

## Node.js and backend

| Internals            | Theory                       | Network           | Technique        | Problems             |
|----------------------|------------------------------|-------------------|------------------|----------------------|
| 🟦 Nonblocking I/O   | 🟦 I/O bound tasks           | 🟩 HTTP(S)        | 🟩 Logging       | 🟦 Memory leaks      |
| 🟦 Event Loop        | 🟦 CPU bound tasks           | 🟦 TCP/SSL        | 🟩 Testing       | 🟦 Resource leaks    |
| 🟦 commonjs          | 🟦 Memory bound tasks        | 🟦 UDP            | ⬜ CI/CD         | 🟦 Blocking code     |
| 🟦 ECMA modules      | 🟦 Multilayer approach       | 🟦 TLS            | 🟦 Readable      | 🟦 Data race         |
| 🟦 Network API       | 🟦 Separation of concerns    | 🟦 Websocket      | 🟦 Writable      | 🟦 Graceful Shutdown |
| ⬜ Addons            | 🟦 Inversion of control      | ⬜ SSE            | 🟦 Transform     | 🟦 Dependencies      |
| ⬜ N-API             | 🟦 Dependency injection      | ⬜ HTTP/3 (QUIC)  | ⬜ back pressure |                      |
| ⬜ Webassembly       | 🟦 GRASP for JS and Node.js  | ⬜ Long polling   | 🟩 Buffer        |                      |
| 🟦 npm               | 🟦 SOLID for JS and Node.js  | 🟩 REST           | 🟩 Console       |                      |
| 🟦 node_modules      | 🟦 GoF for JS and Node.js    | 🟦 RPC            | 🟦 Inspector     |                      |
| 🟦 package.json      | ⬜ Distributed systems       | 🟦 Routing        | 🟦 Reliability   |                      |
| 🟦 vm isolation      | ⬜ Highload applications     | 🟦 IP sticky      | 🟦 Quality       |                      |
| 🟦 command line args | 🟦 DDD                       | 🟦 DoS            | 🟦 Availability  |                      |
| ⬜ Node.js CLI       | 🟦 Clean architecture        | 🟩 DDoS           | 🟦 Flexibility   |                      |
| 🟦 Streams           | 🟦 Domain in the middle      | 🟩 XSS            |                  |                      |
| 🟦 Clustering        | 🟦 Message Queue             | 🟦 Path traversal |                  |                      |
| ⬜ Load balancing    | 🟦 Transport-agnostic server | 🟩 CSRF           |                  |                      |
| ⬜ Serverless clouds | 🟦 Framework-agnostic app    | 🟦 DNS            |                  |                      |
| ⬜ FaaS clouds       | ⬜ Interactive applications  | 🟦 Fetch          |                  |                      |
| 🟦 Debugging node.js | ⬜ Real-time applications    | 🟦 zlib           |                  |                      |
| 🟦 crypto            | 🟦 CQS and CQRS              |                   |                  |                      |
| ⬜ SharedArrayBuffer | 🟦 Event Sourcing            |                   |                  |                      |
| 🟦 child_process     | 🟦 Shared memory             |                   |                  |                      |
| 🟦 worker_threads    |                              |                   |                  |                      |
