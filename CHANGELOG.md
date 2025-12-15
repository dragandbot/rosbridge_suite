# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.12.0] - 2025-12-15

### Added

- Check for Single Point Of Control (SPOC).

***

## [0.5.2] - 2014-03-14
 * Added error messages on result=False When call_service returns False as result, values contains the error message. (Pro)
 * Specific IP adress binding using roslaunch (Steffel Fenix)
 * support publishing non-ascii letters (furushchev)
 * Fixed wrong unicode encoding (Pro)
 * adding missing dependency in rosbridge_library (jihoonl)
 * Decorated call_service item as list (nus)
 * merging changes of groovy-devel into hydro-devel (jihoonl)
 * First attempt adding latching support for topic publishers (adamantivm)

2013-10-31 - **0.5.1**
 * Implement multiple subscriptions to latched topics (fixes #1) (RainCT)
 * more natural json for call service result (OTL)
 * Add service call fail handling (OTL)

2013-07-16 - **0.5.0** 
 * Adds travis CI script (rctoris)
 * current authentication op code added (rctoris)
 * Removes global bin installation (jihoonl)
 * Moves Protocol Specification into repository (baalexander)

2013-04-08 - **0.4.4**
 * Adds build_tool dependency (jihoonl)
 * Adds Jihoon and Russell as maintainers (jihoonl)

2013-04-03 - **0.4.3**
 * Adds CMake List for meta-package (jihoonl)

2013-04-03 - **0.4.2**
 * Adds authentication via rosauth (rctoris)
 * Fixes launch file locations (rctoris)
 * Adds SSL support (rctoris)

2013-03-07 - **0.4.1**
 * Adds message_generation build dependency (jihoonl)
 * Fixes import issue with rosapi (jihoonl)

2013-03-05 - **0.4.0**
 * Cleans up meta package (jihoonl)
 * Cleans up tests (jihoonl and baalexander)
 * Removes test dependency (dgossow)
 * Fixes "int is not iterable" bug (baalexander)
 * Catkinizes tests (baalexander)
 * Catkinizes packages (baalexander)

