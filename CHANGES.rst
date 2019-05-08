#####################
grafana-wtf changelog
#####################


in progress
===========
- Improve report output. Add title, folder, uid, created, updated fields for dashboards.

2019-05-08 0.6.1
================
- Improve progressbar behavior
- Upgrade required packages to their recent versions

2019-05-08 0.6.0
================
- Add "--concurrency" option to run multiple requests in
  parallel as requested through #2. Thanks, `@jangaraj`_.
- Extend non_leaf_nodes with "list" and "links"
- Improve logging

2019-05-07 0.5.0
================
- Raise the limit for ``search_dashboards()`` to its maximum value (5000).
  Thanks, `@jangaraj`_.

2019-05-07 0.4.0
================
Slightly improve the situation with large Grafana installations, see #2.
Thanks, `@jangaraj`_.

- Add option ``--cache-ttl`` for controlling the cache expiration time
- Improve error logging when hitting Grafana unauthorized
- Improve performance of search routine

.. _@jangaraj: https://github.com/jangaraj

2019-04-21 0.3.1
================
- Add progress indicator
- Improve logging and reporting


2019-04-20 0.3.0
================
- Add ``grafana-wtf log`` subcommand for displaying edit history


2019-04-10 0.2.0
================
- Add missing dependency "jsonpath-rw"


2019-01-24 0.1.0
================
- Add proof-of-concept implementation
- Add Grafana API key token authentication
- Add HTTP response caching and "--drop-cache" option