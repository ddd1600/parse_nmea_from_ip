This pseudo-gem (not a gem) is being used to parse nmea data streaming over ip using the gps2ip app on iphone.

I have only tested this app for use when its ONLY sending "GLL"-type NMEA messages.

To use, include the "codebase" (hoho) in your project, and run `source 'grab_data.rb'` or something equivalent.

Then just run: `GrabData.new(url, port).go` and it should grab your location for you.
