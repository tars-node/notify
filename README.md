# @tars/notify



Report service (framework) messages (alarms) to the 'tars' platform.



## report(message[, id])



Report the message to the platform and view it on the web management page.



*Message: message content (required)

*"Id": service thread (process) id, * default value is process.pid*



## notify(message[, level, id])



Report the notification information to the platform.



*Message: notification content (required)

*"Level": the level of notification content, which is level enumeration, * the default value is level.notifynormal*

*"Id": service thread (process) id, * default value is process.pid*



`There are three options in the level enumeration:



*"Level. Notifynormal": normal (default)

*"Level. Notifywarn"

*'level. Notifyerror'



The platform shall give convergence alarm to the reported abnormality every 10 minutes.
