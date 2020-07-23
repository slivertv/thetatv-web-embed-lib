# THETA.tv Web Embed


## Multi-Channel View
This is the default embed view, and allows users to select a channel to view.

![Multi-Channel View](http://sliver-assets.imgix.net/website/images/embed_multichannel.png)

**URL:**
```
https://embed.theta.tv/e?partner={partner_id}
```

----

## Single Channel View
This view displays only a single predetermined channel. The stream will automatically appear when the  channel goes online. 

![Channel View](http://sliver-assets.imgix.net/website/images/embed_channel.png)

**URL:**
```
https://embed.theta.tv/e/channel/{channel_alias}?partner={partner_id}
```


----
## Stream View
Displays only the stream and stream information for a single channel. 

![Stream View](http://sliver-assets.imgix.net/website/images/embed_stream.png)

**URL:**
```
https://embed.theta.tv/e/stream/{channel_alias}?partner={partner_id}
```

----
## Chat View
Displays only the chat for a single channel. Can be used in combination with the Stream view to create your own page layouts. 

![Chat View](http://sliver-assets.imgix.net/website/images/embed_chat.png)

**URL:**
```
https://embed.theta.tv/e/chat/{channel_alias}?partner={partner_id}
```


----
# Iframe Embed
You can manually embed THETA.tv content using an IFrame.

```
<iframe src=”https://embed.theta.tv/e/chat/{channel_alias}?partner={partner_id}” border=”0” width=”100%” height=”100%”/>
```


----
# JS SDK
Coming Soon.

