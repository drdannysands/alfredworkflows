Doximity Dialer Workflow

I am a physician and clinical informaticist. I use Doximity Dialer to call back patients, which sets my caller ID to be my practice phone number. I wanted to be able to highlight a phone number and enter it into the Doximity Dialer page. This can't be done with a simple HTML query string.

Obviously, you need to be subscribed to Doximity.com to use this (which I think is restricted to US healthcare professionals).

So I created a workflow that opens Doximity Dialer page with phone number already entered. This can be used as a Universal Action (which is most powerful) when you've highlighted the phone number to call or using keyword "dd" followed by phone number string.

If you don't use Chrome as your browser, you can set the Environment Variable browserName to your browser application name (click on the [x] symbol in the upper right of the workflow palette).

Hope you find this useful. All suggestions welcome.

Danny Sands
danny@drdannysands.com
www.drdannysands.com

https://github.com/drdannysands/doximitydialer.git