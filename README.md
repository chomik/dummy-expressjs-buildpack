# dummy-expressjs-buildpack

The purpose of this buildpack is to provide simple server that serves static
files.

It requires node and npm to run.

It installs `express` server, adds `server.js` file and sets default procfile
to:

    web: node server

You can customize the path used for server for static files using
`CUSTOM_STATICS_PATH` environment variable. The default is `dist`.
