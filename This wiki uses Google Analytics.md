---
title: This wiki uses Google Analytics
tags: 
date: 2021-01-01 11:08:51
---

# This wiki uses Google Analytics

<<i18n disclaimer_common $:/plugins/sycom/g-analytics>>

<$reveal type="match" stateTitle="$:/temp/GoogleAnalyticsDNT" text="yes">

<<i18n disclaimer_dnt $:/plugins/sycom/g-analytics>>
</$reveal>

<$reveal type="nomatch" stateTitle="$:/temp/GoogleAnalyticsDNT" text="yes">
   <$reveal type="nomatch" stateTitle="$:/temp/GoogleAnalyticsGDPRoption" text="no">

<<i18n disclaimer_gdpr $:/plugins/sycom/g-analytics>>
   </$reveal>
   <$reveal type="match" stateTitle="$:/temp/GoogleAnalyticsGDPRoption" text="no">

<<i18n disclaimer_nogdpr $:/plugins/sycom/g-analytics>>
      <$reveal type="match" stateTitle="$:/plugins/sycom/g-analytics/settings/track_all" text="yes">
<<i18n disclaimer_internal $:/plugins/sycom/g-analytics>>
      </$reveal>

<<i18n disclaimer_settings $:/plugins/sycom/g-analytics>>
   </$reveal>
</$reveal>


---
### Tags
