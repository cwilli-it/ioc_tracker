# ioc_tracker
IOC Tracker is used to import and export indicators of compromise. It can also enrich existing indicators from open source threat intel (VT)

**Using IOC Tracker**

IOC Tracker includes search functionality to filter on several different fields along with some custom searches.

Syntax
 - search using type: qualifier
 - search using AND
 - search using OR
 - syntax = <searchstring> type:domain
 - example: <domain> AND <domain> type:domain
 - example: <domain> OR <domain> type:domain
 - Fixed bug on close (Data Scrub)
  
  **Other Functionality**
 
 1. Bulk addition of IOC
 2. Automatic labeling of IOC type (domain, ip, file)
 3. Export IOC content into a Splunk lookup friendly format
 4. Export data to xlsx
 5. Automatic purging of aged IOC.
 6. Bulk edits of IOC.
