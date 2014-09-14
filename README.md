ascl-json
=========

### ASCL public data in json format. Probably.

There are nine fields:  

| Field       | Description          |
| ------------- |------------- |
| ascl id     | This is rendered without the preface ascl:. This is a unique identifier assigned by the ASCL following the pattern *yymm:xxx*, where *yy* = year of publication in the ASCL, *mm* = month of publication, *xxx* = sequential number assigned in order of publication | $1600 |
| code title      | usually a short code name separated with a colon from a one-line description or longer name of the code      | 
| credit | code author(s) name(s)      |
| abstract | brief description of the code      |
| site | code's website or download location      |
| ref | refereed paper using or describing the code      |
| bibcode | bibcode as used for ADS      |
| topic ID | thread ID for the code's discussion thread on the forum; the URL follows the pattern: *http://ascl.net/phpBB3/viewtopic.php?t=xxxxx*, where *xxxxx* is the topic ID     |
| views | the number of times the code as been viewed on the new infrastructure (IOW, since July 10, 2014)      |

**NOTES:** 

One code (MasQU) that does not have a download site listed and instead has an email address in the Site field. I think that is the only one like that. 

Because there is a lag between indexing codes in the ASCL and ADS ingestion, some bibcodes will not work to retrieve its ADS entry (because it hasn't been created yet)

If something is weird in the dataset(s), please let me know. 
