## v2.3.6 ##
 * Feature: prefetch images from ZDocs and store in a S3 cache. 
   rewrite image URLs in HTML - AH will fetch from cache.
 * Fix: update 'failed' status for jobs that didn't pass input validation
 * Fix: cached jobs fetch files from the correct S3 path  