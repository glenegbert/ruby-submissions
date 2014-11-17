
### Breath of Fresh Air

### Pitch

Get a notification when the air quality in your area is likely to trigger health problems for you.

### Description

Users come to the website and enter in: locations of their choice, phone or email, and select from 1 or more of 6 general health concern categories (like this http://www.epa.gov/aircompare/health.htm ).  They then elect to receive notifications when observed conditions and/or forecasted conditions in the geographic areas they listed are at levels that are likely to aggravate the medical conditions they identified. Additionally users will be able to generate a data visualization that shows annual trends related to their specific health concern category for the geographic area they identified.

### Target Audience

This application will be used by individuals who suffer from health problems that are aggrevated by poor air quality.

### Integrations

* What OAuth provider makes sense for this audience? Google - saved searches
* What Data.gov data or API will you use? http://www.airnowapi.org/docs/AirNowAPIFactSheet.pdf
* Any other integrations?
* 

Iteration 1 
- Plan to Have 
- Rough Site View Templates
- User can select 1 location and one health issue and see current conditions and forecasts 
- User can sign into the site with OAuth

Nice to Have 
- Set up VPS
- clean UI

Iteration 2 
Plan to Have 
-clean UI
-app sends notifications
-app exposes JSON API - that shows historically high risk days/months for a health concern and zip code 
basic plan for Ruby gem 
-VPS in place

Nice to Have 
-background workers
-Ruby Gem

Iteration 3 
Plan to Have 
-app sends notifications with background workers
-Ruby Gem Working 

Nice to Have 
- front end bells and whistles

******************************************************************************************************************
### Neighborhood Finder


### Pitch

Filter neighborhoods by RE price range, school quality, work commute time, education commute time.

### Description

This app lets users filter neighborhoods based on their preferences for home cost, school quality, school distance, and work commute time.  The app outputs a regional map higlighting zip codes that match the user's preferences.

### Target Audience

The target audience for this app is individuals planning to buy a home in the near
future who are concerned with finding quality education for their children and minimizing commute time to school and work.

### Integrations

* What OAuth provider makes sense for this audience? Google
* What Data.gov data or API will you use? 
                                          http://www.zillow.com/howto/api/APIOverview.htm
                                          http://www.greatschools.org/api/docs/main.page
* Any other integrations?
