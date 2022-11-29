# ExcelMaya

## _This is mostly for archival purposes and is not being maintained.  (Created ~2019)_

ExcelMaya was born out of _boredom_. In an effort to prove that the PayMaya (now Maya) documentation was easy to understand and PayMaya Checkout is easy to integrate, I sought to put it on MS Excel. This was created on a Mac machine and will probably not work on other platforms (yet?🤔). It also probably doesn't work on Macs anymore either.

## How It Works

The dropdown fields are populated via the Items sheet. Upon clicking `Submit`, `execShell` is used to invoke a `curl` command that sends the details to PayMaya's endpoints to generate a `checkout`.  The resulting page is then viewable under the `CLICK ME` cell, where the customer can pay for the items.

## Links

[Maya Developer Hub](https://developers.maya.ph/)
