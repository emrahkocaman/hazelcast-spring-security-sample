hazelcast-spring-security-sample
================================

A sample project to see the behaviour of Spring Security Concurrency Control mechanism with Hazelcast HTTP session clustering 
and reproduce the behaviour mentioned in below Hazelcast Google group and GitHub issue. 
https://groups.google.com/forum/#!topic/hazelcast/5LgM9LE-V_M
https://github.com/hazelcast/hazelcast/issues/3049

It's a basic Spring MVC project with Spring Security, created using Spring Tool Suite templates.

After deploying the project to your web container, go to the URL:
http://localhost:YOUR_SERVER_PORT/test/admin and login with credentials -> user/password

Try logging out and logging in again and there should be no problem.
