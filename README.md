# keepass2-auto-type-or-start
KeePass2 comes with the AutoType feature. Using Ubuntu with Unity you can keybind a certain combination
to fill in the credentials for the window you are currently in.
For this to work however, KeePass2 must already be running.
This is a simple script you can install to `/usr/bin` using `make install`.
Instead of `keepass2 --auto-type` you bind your key combination to `keepass2-auto-type-or-start`.
When you hit your combination from any window, and KeePass2 is not running, it will be started, prompting you for
your master password or key file to unlock your database.
With your database unlocked, just Alt+Tab back to the login screen, hit your combination again, and it will autotype
your credentials (assuming you have auto type set up correctly).
