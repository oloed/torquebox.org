---
title: TorqueBox 1.0.0.Beta13 available now
author: Bob McWhirter
version: 1.0.0.Beta13
layout: release
tags: [ releases ]
---
The TorqueBox Ruby application platform has reached 1.0.0.Beta13 and is [available now](/download/).

This release includes a handful of improvements, including some for hybrid Java/Ruby shops:

* Finer-grained control by supporting web.xml
* Support for jboss-web.xml and \*-ds.xml

And some for everyone:

* Runtime pool management for non-threadsafe mode
* Specify context-path when deploying with rake

The list of closed JIRA entries:

## Bug

* [TORQUE-9](https://jira.jboss.org/jira/browse/TORQUE-9) - Torquebox not using config/jboss-web.xml to configure jndi references, etc.

## Feature Request

* [TORQUE-8](https://jira.jboss.org/jira/browse/TORQUE-8) - Allow to specify the deploy context path from the rake task
* [TORQUE-10](https://jira.jboss.org/jira/browse/TORQUE-10) - Enable JRuby pooling to be configured manually, even with "threadsafe" Rails (2.2+)

## Task

* [TORQUE-12](https://jira.jboss.org/jira/browse/TORQUE-12) - Re-enable RSpec tests
* [TORQUE-14](https://jira.jboss.org/jira/browse/TORQUE-14) - Document pooling.yml

As always, see the [downloads page](/download/) for all of the downloadable artifacts, 
and the [latest documentation](/documentation/) is also available.
