mailpw_change
=============

**changepw.html**: Simple HTML form. Put it into your *~/html* for example. Change XXXUSERXXX and XXXHOSTXXX according to your uberspace user and host name.

**changepw.py**: Put it into your *~/cgi-bin* and give all users executable rights (`chmod a+x ~/cgi-bin/changepw.py`).

Python script will check if user exists, if new password and repeated new password match and also if old password is correct.


Dependencies of Python script: python-cdb

Install on your uberspace with
`pip install python-cdb --user`


This script probably could be extended to allow each IP only 5 password changes per day to avoid misuse.
