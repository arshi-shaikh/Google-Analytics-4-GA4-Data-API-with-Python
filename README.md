# Google-Analytics-4-GA4-Data-API-with-Python

Important links:

**Google Quickstart guide:** https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries

**API dimensions and metrics:** https://developers.google.com/analytics/devguides/reporting/data/v1/api-schema

**Google developer's guides:** https://developers.google.com/analytics/devguides/reporting/data/v1/rest/v1beta/properties https://googleapis.dev/python/analyticsdata/latest/data_v1beta/beta_analytics_data.html

**The overview of the process:**
>>>Get API keys: create a GCP project, authorize Google Analytics Data API
>>>create a service account, create JSON keys for the account.
>>>Add service account as a viewer to your GA4 propert(Admin->User Management)
>>>Install google-analytics-data package.
>>>Set os.environ["GOOGLE_APPLICATION_CREDENTIALS"] = 'your_api_key.json'
>>>Send request, get output. Done!
