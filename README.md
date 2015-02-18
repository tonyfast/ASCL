ASCL
=========

### This repository stores tools useful for working with the Astrophysics Source Code Library (ASCL; ascl.net) and its data in various formats.


---

#### ASCL public data in json format. Probably.

There are nine fields:  

| Field       | Description          |
| ------------- |------------- |
| ascl id     | rendered without the preface *ascl:*. This is a unique identifier assigned by the ASCL following the pattern *yymm:xxx*, where *yy* = year of publication in the ASCL, *mm* = month of publication, *xxx* = sequential number assigned in order of publication |
| code title      | usually a short code name separated with a colon from a one-line description or longer name of the code      | 
| credit | code author(s) name(s)      |
| abstract | brief description of the code      |
| site | code's website or download location      |
| ref | refereed paper using or describing the code      |
| bibcode | bibcode as used for ADS      |
| topic ID | thread ID for the code's discussion thread on the forum; the URL follows the pattern: *http://ascl.net/phpBB3/viewtopic.php?t=xxxxx*, where *xxxxx* is the topic ID     |
| views | the number of times the code as been viewed on the new infrastructure (IOW, since July 10, 2014)      |

**NOTES:** 

One code (MasQU) does not have a download site listed and instead has an email address in the Site field. I think that is the only one like that. 

Because there is a lag between indexing codes in the ASCL and ADS ingestion, some bibcodes will not work to retrieve its ADS entry (because it hasn't been created yet).

If something is weird in the dataset, please let me know. 

---


#### ASCL public data in xml format. Maybe.

There are nine fields:  

| Field       | Description          |
| ------------- |------------- |
| ascl_id     | rendered without the preface *ascl:*. This is a unique identifier assigned by the ASCL following the pattern *yymm:xxx*, where *yy* = year of publication in the ASCL, *mm* = month of publication, *xxx* = sequential number assigned in order of publication |
| title      | usually a short code name separated with a colon from a one-line description or longer name of the code      | 
| credit | code author(s) name(s)      |
| abstract | brief description of the code      |
| site | code's website or download location      |
| ref | refereed paper using or describing the code      |
| bibcode | bibcode as used for ADS      |
| topic_id | thread ID for the code's discussion thread on the forum; the URL follows the pattern: *http://ascl.net/phpBB3/viewtopic.php?t=xxxxx*, where *xxxxx* is the topic ID     |
| views | the number of times the code as been viewed on the new infrastructure (IOW, since July 10, 2014)      |

**NOTES:** 

One code (MasQU) does not have a download site listed and instead has an email address in the Site field. I think that is the only one like that. 

Because there is a lag between indexing codes in the ASCL and ADS ingestion, some bibcodes will not work to retrieve its ADS entry (because it hasn't been created yet).

If something is weird in the dataset, please let me know. 
