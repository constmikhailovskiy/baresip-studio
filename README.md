This is very basic Android Studio project implementing baresip
(https://github.com/alfredh/baresip) based SIP User Agent.

Currently includes TLS transport, PCMU/PCMA and opus codecs, as well as
ZRTP and (DTLS) SRTP media encapsulation.

The static libraries and include files in distribution directory have
been produced using https://github.com/alfredh/baresip-android after
applying reg.c-patch to re/src/sipreg/reg.c.  The patch is needed due to
re timer sometimes firing too late.

After cloning the project, in android-studio:

- Open an existing Android Studio project

- File -> Invalidate Caches / Restart -> Invalidate & Restart

Now available also in Google Play store.

Feedback welcome.
