# InnerTube Blobs Archive

This is a collection of InnerTube requests/responses. 

The JSON comes from YouTube around February 14-15th 2026, on macOS 26.3 using Firefox 147.0.3 with no extensions.

The Protobuf blobs come from an emulated device running Android 8.1 using an unmodified copy of YouTube 20.14.43 (a client from April 2025).

This archive could be useful towards eventually reimplementing the InnerTube API, and perhaps later down the line a Polymer/Kelvar/Delhi "revival" project once that gets considered old enough.

## How do I use this?

I don't really know. All I'll say is that:

* The InnerTube API is most likely defined as Protobuf schemas.
* If you're going to recreate the InnerTube APIs, *please* use Python. It's what Google is using for InnerTube anyways.
* The output of InnerTube depends if you're on the web desktop or mobile version of YouTube. I should definitely look into the *web mobile* version of YouTube some day.
* The Protobuf blobs are NOT schemas. You will have to decompile this yourself.
