=======
Support
=======

Support for CanModule is given CERN wide.

**Problems, Issues and Requests** should be created as CERN `Jira`_ Tickets:

* Project= OPC UA in JCOP (OPCUA)
* Components= CanModule
* Assignee= Michael Ludwig

Please provide traces of your situation and information about your project context. We will sort it out together.

Many CAN related problems have been solved in the past by

* correcting the bus termination (should be terminated in most cases)
* correcting the bus bitrate to match the slaves (125000bits/sec is default)
* driver problems, vendor libs not found
* small configuration errors

And yes, there can be bugs as well.

More **personal** ways to get help or report problems:

* You can send me an `Email`_ or call me 163095 or visit me for a coffee.
* Please also take a look at `JiraSearch`_ for already existing issues.

.. _Jira: https://its.cern.ch/jira/secure/Dashboard.jspa
.. _JiraSearch: https://its.cern.ch/jira/browse/OPCUA-1362?jql=assignee%20%3D%20currentUser()%20AND%20component%20%3D%20CanModule%20AND%20project%20%3D%20OPCUA
.. _Email: mailto:michael.ludwig@cern.ch?subject=CanModule_issue_found&body=Hello Michael,