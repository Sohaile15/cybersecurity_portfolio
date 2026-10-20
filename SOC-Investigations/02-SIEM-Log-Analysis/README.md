SIEM Log Analysis Using Splunk

Project Overview

Used Splunk Enterprise to investigate sample web server logs, identify error patterns, and analyze client IP activity and requested URLs.

Tools Used

* Splunk Enterprise
* Search Processing Language (SPL)
* Sample web access logs

Investigation

* Ingested and validated log data in Splunk.
* Analyzed HTTP errors and hourly event trends.
* Investigated activity associated with a selected client IP.
* Examined requested URL paths and HTTP status codes.

Key Findings

* Identified 427 events matching the search term error.
* Found repeated matches for /cart/error.do.
* Investigated requests to /passwords.pdf, which returned HTTP 404 responses.
* Reviewed client IP activity across actions, URL paths, and status codes.

These findings are observations from sample training data and do not establish that a real attack occurred.

Evidence

Screenshots of data ingestion, SPL searches, event analysis, and investigation results are available in the Evidence folder.

Skills Demonstrated

* SIEM log analysis
* SPL queries
* Event investigation
* HTTP log analysis
* Basic security investigation and documentation

Limitations

This project uses sample training data, not live production logs. Further work could include investigating additional scenarios and building a Splunk dashboard.
