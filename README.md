# lc-single-domain-asynchronous-http
UPDATE: Turns out this is only a hack to let your interface unblock while doing a lot of requests, but it does not actually do the (same domain) calls in an asynced way.  The calls still happen in sequence.

Send multiple (psuedo-asynchronous) HTTP Requests to the same domain in Livecode Community.

Just click either one of the 2 buttons, look at global variable array 

Trigger Sequential or Asynchronous downloads.

Whole thing works around a scheduler.

We skip the built in LibURL Callback function, and made our own handler where we control the update interval.

No error handling code

Planning on building func version of command

hope it makes life easier, for others who need to work with the same domain.
