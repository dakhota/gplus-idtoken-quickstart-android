gplus-idtoken-quickstart-android
================================

A slightly modified version of [gplus-quickstart-android](https://github.com/googleplus/gplus-quickstart-android),
based on a [StackOverflow response](https://stackoverflow.com/questions/17547019/calling-this-from-your-main-thread-can-lead-to-deadlock-and-or-anrs-while-getti/17547891#17547891)
by [David Cain](https://github.com/DavidCain).

It retrieves an [`id_token`](https://developers.google.com/accounts/docs/CrossClientAuth) after logging in with Google+.

Note: I removed circles support from the original quickstart example so that a narrower Google+ scope would be sufficient.
