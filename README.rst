LimeSurvey - Survey application
===============================

`LimeSurvey`_ is a user-friendly web application that enables users to
develop and publish surveys, and collect responses, without doing any
coding. Users can use rich text in questions and messages, using a rich
text editor, and images and videos can be integrated into surveys.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- LimeSurvey configurations:
   
   - Installed from upstream source code to /var/www/limesurvey
   - Admin area available from example.com/admin

     **Security note**: Updates to LimeSurvey may require supervision so
     they **ARE NOT** configured to install automatically. See `LimeSurvey
     documentation`_ for upgrading.

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL: username **root**
-  Adminer: username **adminer**
-  LimeSurvey: username **admin**


.. _LimeSurvey: https://www.limesurvey.org/
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _LimeSurvey documentation: https://manual.limesurvey.org/Upgrading_from_a_previous_version
.. _Adminer: https://www.adminer.org/
