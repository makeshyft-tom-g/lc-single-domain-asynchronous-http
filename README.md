# lc-single-domain-asynchronous-http
Send multiple asynchronous HTTP Requests to the same domain in Livecode Community

Just click either one of the 2 buttons, look at global variable array HTTPDownload

Trigger Sequential or Asynchronous downloads.

Whole thing works around a scheduler.

We skip the built in LibURL Callback function, and made our own handler where we control the update interval.

No error handling code

Planning on building func version of command

hope it makes life easier, for others who need to work with the same domain.
