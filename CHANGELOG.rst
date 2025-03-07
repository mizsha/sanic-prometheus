Changelog
=========

Version 21.12.0 (on Dec 29 2021)
------------------------------
* added sanic 21.12.0 support
* switch to calver versioning

Version 0.2.1 (on Oct 12 2020)
------------------------------
* Changed the sanic request ctx for __START_TIME__ for the middleware is going to be deprecated, added the newer ctx way for adding custom objects. (by Arvind Mishra)

Version 0.2.0 (on May 13 2020)
-------------------------------
* Custom metrics + refactoring (@axyjo and @skar404)


Version 0.1.10 (on  Jun 20 2019)
-------------------------------
* Ignore OPTIONS

Version 0.1.8 (on Apr 9, 2019)
-------------------------------
* Add metrics_path kwarg to monitor() in order to customize /metrics

Version 0.1.7 (on Jan 25, 2019)
-------------------------------
* Make it work with newer versions of prometheus-client (>= 0.5.0)
  (not backwards compatible with earlier versions of the library)

Version 0.1.6 (on Jan 25, 2019)
-------------------------------
* Python 3.7 support (@wallies)
* Restrict prometheus-client version that's safe to work with (@aviv-ebates)

Version 0.1.5 (on May 17, 2018)
-------------------------------
* Add websocket support (@SirEdwin)
* Add http_status label to request latency metric (@mmniaziqb)

Version 0.1.4 (on Aug 1, 2017)
------------------------------
Add multiprocessing support

Version 0.1.3 (May 8, 2017)
---------------------------
FIX: remove early return that kills other middlewares.

Version 0.1.2 (Apr 25, 2017)
----------------------------
Starting from 0.5.0 Sanic has http[s]:// prefix
in request.url, switch to using request.path instead.

Version 0.1.0 (Apr 4, 2017)
---------------------------
First public version of sanic-prometheus
