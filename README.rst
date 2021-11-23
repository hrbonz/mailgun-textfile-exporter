###############################################################################
mailgun-textfile-exporter - mailgun stats exporter using node-exporter textfile
###############################################################################

A prometheus textfile exporter for mailgun metrics. Stats are gathered from the
mailgun API and exposed as 
To keep things fast, the metrics get initiated by a first, potentially slow,
call to the backend.


References
==========

* https://documentation.mailgun.com/en/latest/api-stats.html

License
=======

mailgun-textfile-exporter is published under a BSD 3-clause license, see the
LICENSE file distributed with the project.
