# noticefeed
The Module to fetch Notice data feed from the The Gazette REST API


Module Name : noticedata

# Purpose of this module :
-------------------------

This module is to fetch the Notice data feed from the The Gazette REST API. The module contains following fields and pagination. Each page will have 10 records.

* Id
* Title with a link to the notice
* Publish date 
* Content


hook menu name : noticedatadisplay

# Steps to enable this module :
-----------------------------

1. Download and place this module under the custom folder (say: sites/all/modules/custom). 

2. As a drupal admin go to ?q=admin/modules and enable this module.

3. Clear the drupal cache after enabing the module : Go to ?q=admin/config/development/performance and click "Clear all caches".

4. Now hit the following url <domain_name>/noticedatadisplay, details will be fetched from the Gazette REST API.
