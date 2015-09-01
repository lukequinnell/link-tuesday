Link Tuesday
============

This is an initial attempt at getting all HipChat messages containing '#linkTuesday' that have been posted within the configured room copied over to a dedicated Confluence page automatically.

Requirements
------------

* Python 2.7.6+
* jsawk - https://github.com/micha/jsawk

Installation
------------

1. Ensure Jsawk is installed on the environment.

2. Add the HipChat 'AUTH_TOKEN' value to the hipchat bash script.

3. Add the 'userId' and 'userSecret' values to the confluence bash script.

4. Add the correct API URLs

Running
-------

1. Run the following command - `bash confluence` within the root of this project.