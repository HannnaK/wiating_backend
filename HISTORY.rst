=======
History
=======
1.6.0 (2020-11-14)
------------------
* Check if moderator has an access to the service

1.5.0 (2020-11-02)
-----------------
* Add reviewed_at parameter to get_logs

1.4.1 (2020-11-01)
------------------
* Endpoint log_reviewed return HTTP 400 if no log found

1.4.0 (2020-11-01)
------------------
* New endpoint log_reviewed

1.3.2 (2020-10-27)
------------------
* Fix bug with saving empty report reason. It should be None, not [None].

1.3.0 (2020-10-19)
------------------
* report_reason parameter for search_points

1.2.0 (2020-10-10)
------------------
* Regular user can get its log by get_log endpoint

1.1.0 (2020-10-04)
------------------
* Add report endpoint
* Fix get_user_log behavior in case of empty body

0.1.0 (2019-11-11)
------------------

* First release.
