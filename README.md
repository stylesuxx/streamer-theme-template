# Streamer Theme template
> This is a template for a streamer theme.

A theme contains a *conf.json* file and background image for each of the layouts.
Different layouts refer to the amount of video feeds you would like to show.

You can have different layouts for 1, 2, 3, 4 and 6 feeds.

## Background image
The background image spans the total size of the stream, so the suggested size of the background image is 1920x1080px.

> If your background image is 1024x768px, the base canvas for your stream will be of this size.

From the examples you can see, that the "No signal" placeholders are part of the background image itself.

## Config file
The *conf.json* holds the information for each of the layouts. It cointains information where to position the feeds and width of the feed. The height of the feed is scaled according to the  width.

The config file also contains information about where to place the pilot names in each of the layouts. Further it allows to adjust font settings.