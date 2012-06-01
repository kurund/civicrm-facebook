civicrm-facebook
================

Allow admin to post CiviCRM events to Facebook

===========================
Instructions
===========================

1. Create a new facebook app. Check below links
   https://developers.facebook.com/apps
   https://developers.facebook.com/docs/guides/appcenter/
2. Apply this patch.
3. Create packages/facebook diretory in civicrm packages folder
4. Download and unzip facebook PHP SDK in above folder.
   https://developers.facebook.com/docs/sdks/
3. Run http://<your site name>/civicrm/menu/rebuild?reset=1
4. That's it, now you will have "Publish to Facebook" tab in your
   events configuration page.
