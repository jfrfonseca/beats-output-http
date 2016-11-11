html-filebeat-aggregator-visualizer
===================================

[FileBeat] is a simple file-monitoring tool. It allows for someone to see every change incurred to a file from distance, and aggregate the changes of multiple files using [LogStash], or even [Redis].

It is cool and all, but fowarding file changes to Redis or LogStash requires quite a lot of hardwork and infrastructure. Its overkill for regular development needs of log aggregation and visualization.

This *HTML FileBeat Logs Aggregator & Visualizer* is a simple web interface for FileBeat logs. Messages sent by multiple FileBeat instances are received by a simple Python [Flask] server that serves HTML pages. Just. Like. That.

Those HTML pages have some bells and whistles too, like [RegEx] filters, highlighting and counters and charts. But that is still a dream.

EARLY DEVELOPMENT STAGE
