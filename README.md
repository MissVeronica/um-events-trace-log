# UM Events Trace Log
A debug tool for tracing UM events: nonce events, redirect events, password reset events, email validation events and login errors.

Last events are saved in the options table with option name um_events_trace_log and can be displayed by the shortcode.

## Shortcode
[um_events_trace_log]

The shortcode will list the selected events in reverse order with the following items:

1. Time
2. User ID
3. User Name
4. IP
5. Status
6. Redirect URL / Nonce values / Reset pwd / Activation Hash / Login
7. Redirect by: line
8. HTML Code
9. Priority Role (WP Roles)

Reload the page with the shortcode to list actual events.

## Display failures
1. Remove the shortcode page from UM Restrictions.
2. Disable WP Plugin or web server caching for the shortcode page.

## Updates
1. Version 3.2.0 Fixed ref to function wp_nonce_tick
2. Version 3.4.0 Updated for UM 2.8.3


## Installation
Install by downloading the ZIP file and install as a new Plugin, which you upload in WordPress -> Plugins -> Add New -> Upload Plugin.

Activate the Plugin: Ultimate Member - Events Trace Log

Settings at UM Settings -> Misc

1. Events Trace Log User ID's or @ 	
2. Events Trace Log User IP addresses 	
3. Events Trace Log max number of log entries 	
4. Log nonce events 	
5. Log redirect events 	
6. Log password reset events and login errors	
7. Log email validation events
