# Template Web Monitoring

The purpose of this template is to monitor the availability of websites.
## MACROS
- {$PORTAL} - Site / portal name

- {$SITE_STRING} - Text to be located within the monitored page.

- {$SITE_URL} - URL to be monitored.

## TRIGGER

- Site {$PORTAL} is responding with error
Fires whenever an error is detected on the site.

- Access time to the {$PORTAL} portal is slower than normal
Fires whenever the minimum response time of the site is above the average of 10 minutes of the last hour.