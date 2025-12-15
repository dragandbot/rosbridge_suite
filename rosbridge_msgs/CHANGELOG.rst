# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.12.0] - 2025-12-15

### Added

- Check for Single Point Of Control (SPOC).

***
0.11.9 (2020-05-27)
-------------------

0.11.8 (2020-05-21)
-------------------

0.11.7 (2020-05-13)
-------------------

0.11.6 (2020-04-29)
-------------------

0.11.5 (2020-04-08)
-------------------

0.11.4 (2020-02-20)
-------------------

0.11.3 (2019-08-07)
-------------------

0.11.2 (2019-07-08)
-------------------

0.11.1 (2019-05-08)
-------------------

0.11.0 (2019-03-29)
-------------------
* Additional client information websocket (`#393 <https://github.com/RobotWebTools/rosbridge_suite/issues/393>`_)
  * Add package rosbridge_msgs.
  * rosbridge_server: Publish additional information about connected clients.
  * rosbridge_server: Make ClientManager's add_client/remove_client methods thread safe.
  * rosbridge_server: Rm unnecessary publishing.
  * rosbridge_msgs: Cleanup/fix dependencies.
* Contributors: Hans-Joachim Krauch
