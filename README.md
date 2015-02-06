# meteor-downgrade-issue

This is related to: https://github.com/meteor/meteor/issues/3653

## How to reproduce

* Start a Ubuntu 14.04 (We tested on Digital Ocean)
* Just clone this repo
* run it with meteor

You'll get this message:

~~~shell
=> Started proxy.
=> Started MongoDB.

Changes to your project's package version selections:

meteorhacks:kadira  downgraded from 2.17.5 to 2.17.0

=> Started your app.

=> App running at: http://localhost:3000/
~~~
