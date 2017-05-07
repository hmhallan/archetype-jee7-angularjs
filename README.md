A Clean JavaEE 7 Maven Archetype (jax-rs/angularjs)
=====================

This artifact is installed in the maven central repository and can be automatically installed using the
mvn archetype:generate invocation:

`mvn archetype:generate -Dfilter=com.hallanmedeiros:archetype-jee7-angularjs`

This archetype contains:
 - A beans.xml file for CDI
 - A jax-rs app for REST services
 - A sample rest service
 - A sample front-end written in angularjs that consumes the rest service