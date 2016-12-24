org.webosports.messaging
========================

The Messaging app and service for Lune OS, built with Enyo2 and node.js

Description
-----------
The messaging app is one of the core applications of the operating system and allows to
send messages through various backend services (IM, SMS, ...).

## Contributing

If you want to contribute you can just start with cloning the repository and make your
contributions. We're using a pull-request based development and utilizing github for the
management of those. All developers must provide their contributions as pull-request and
github and at least one of the core developers needs to approve the pull-request before it
can be merged.

Please refer to http://www.webos-ports.org/wiki/Communications for information about how to
contact the developers of this project.


## Building & Installing App

You can develop in the browser like a normal Enyo 2 web app - 
Messaging will use the data in db8SourceMock.js and the mock directory.


To rebuild and install on a LuneOS device attached via USB, run this command in the app directory:

`tools/deploy.sh -i`

Then, in Chrome, surf to `localhost:1122` to debug.

