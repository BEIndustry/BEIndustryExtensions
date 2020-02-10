# BE-Industry Extensions
Welcome to the BEIndustryExtension repository!

This repo is a platform for BE-Industry and all connected partners to work together to extend the BE-Industry solution. 

# Extensibility requests

The following are the types of requests you can submit to unblock your app:

* Add new integration events – Get the event you need to hook-in to a process.
* Change function visibility – For example, make a public function external or a similar change so you can call it from your extension and reuse the business logic.
* Replace Option with Enum – Replace a specific option with an enum that supports your extension. The new type enum is extensible, but all code was written for non-extensible options.
* Extensibility enhancements – Request changes in the application code that will improve extensibility.

We’ll have a look at your request, and if we can we’ll implement it asap. If we can’t we’ll let you know and briefly explain why not. When that happens, don’t be discouraged. Go back to the drawing board, see if you can work it out, and then come back and submit another request.

# Example

Please take a look at the following issue as an example on how to request a new event: https://github.com/BEIndustry/BEIndustryExtensions/issues/1

* The title is written as [Event Request] Object Type; Object Number; Object Name - New Event Name
* The body is split into two parts
** First: A snippet on how the new Event is supposed to look like.
** Second: A snippet to show where the new function is placed. If you need further Code you can also mark them as such with the + symbol at the beginning of the row. That can include new variables or general new lines of code. Anything that is irrelevant to your request can be removed with the use of [...]. Just be sure that your overall goal is still readable.

# Disclaimer

This repo is leaned very closely to the official Microsoft ALAppExtension repository found here: https://github.com/microsoft/ALAppExtensions
