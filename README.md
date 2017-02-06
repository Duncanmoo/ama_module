# ama_module

This assessment has gone pretty awfully and I am leaving this in a non-working
state. My submit and validate handler functions are not being called, perhaps I
am doing something stupid here but I was also having issues with my local dev
environment. This is pretty critical to the functioning of the module.

- I have loaded a default image with the form, could have been random, but chose
something specific.

- I left the accessing of the giphy api until last I have simply used one of
the display formats "downsized".

- I added the giphy_api_key as a variable in the install hook to allow for later
making this an admin configuration option.

- My little giphy_api_find function could do with further abstraction, I went from
the initial objective of displaying a single image, and then generalised that to
allow for additional endpoints.

- The question suggested a whole bunch of bonus options, there is a Drupal module
called giphy, and rather than my sprawling code I should rather have made that
module a dependency and used that module's functions.

- On the template side I didn't really do anything there, just put the template
in place.
