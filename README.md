An AppleScript service to open a folder in WezTerm. This service allows you to quickly open any folder in WezTerm terminal emulator.

Simply right-click on a folder in Finder and select "Open in WezTerm" from the quick action menu to open a new WezTerm window at that location.

## Usage

1. copy this project to `~/Library/Services/`
2. run `/System/Library/CoreServices/pbs -flush`
3. Enable the service in System Settings > General > Extensions > Finder

The service should now appear in the quick action menu when you right-click on a folder in Finder.

If you don't see it immediately, you may need to:
Log out and log back in, or try killing the Finder: `killall Finder`
