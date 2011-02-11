Text-to-Vote
============

Text-to-Vote is a simple web app that allows you to do realtime polling through
SMS.

Text-to-Vote works with the Twilio API, so you'll need an account and phone 
number at Twilio before you can get started. Twilio sells simple, pay as you 
go phone services, and you can sign up for a free account with $30 of free 
credits at http://www.twilio.com.

Installation
============

Installation of Text-to-Vote is as simple as copying the folder, making it 
writeable, editing the configuration file, and pointing Twilio to the correct 
handlers.

1. Copy the folder to your server.

2. Make the folder writeable.

3. Edit /include/config.php

4. Go to http://www.twilio.com and point the Voice URL to
   http://[your server]/[path to Text-to-Vote]/handle_incoming_call.php
   (leave the default POST method selected) and point the SMS URL to
   http://[your server]/[path to Text-to-Vote]/handle_incoming_sms.php

License
=======

Copyright (C) 2010 Rahim Sonawalla (rahim@twilio.com) and Will Light (will@twilio.com).

Released under the MIT license (http://www.opensource.org/licenses/mit-license.php).