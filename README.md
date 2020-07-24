# THETA.tv Web Embed

**Getting Setup**

* Contact us sponsors@thetalabs.org to obtain a partner ID
* Shopify: If you have a shopify account, and would like your viewers to trade their TFuel for discounts on your items, contact us to get setup with our Shopify App for Theta.tv
* Custom Ads: Contact us to display product ads before the streams shown in your apps. 
* Custom content: Contact us to customize the streams to be limited to your affiliate streams, team or org.

----
## Iframe Embed Example
Any of the views below can be manually embedded using an IFrame. Simply replace the SRC url with the view you'd like to use. The channel alias for a particular channel is the last portion of their channel URL on THETA.tv. For example "https://www/.theta.tv/nasa", 'nasa' would be the alias you can use in the URL's below. Contact us to obtain a partner ID.

```
<iframe src=”https://embed.theta.tv/e/chat/{channel_alias}?partner={partner_id}” border=”0” width=”100%” height=”100%”/>
```



### Multi-Channel View
This is the default embed view, and allows users to select a channel to view.

![Multi-Channel View](http://sliver-assets.imgix.net/website/images/embed_multichannel.png)

**URL:**
```
https://embed.theta.tv/e?partner={partner_id}
```

----

### Single Channel View
This view displays only a single predetermined channel. The stream will automatically appear when the  channel goes online. 

![Channel View](http://sliver-assets.imgix.net/website/images/embed_channel.png)

**URL:**
```
https://embed.theta.tv/e/channel/{channel_alias}?partner={partner_id}
```


----
### Stream View
Displays only the stream and stream information for a single channel. 

![Stream View](http://sliver-assets.imgix.net/website/images/embed_stream.png)

**URL:**
```
https://embed.theta.tv/e/stream/{channel_alias}?partner={partner_id}
```

----
### Chat View
Displays only the chat for a single channel. Can be used in combination with the Stream view to create your own page layouts. 

![Chat View](http://sliver-assets.imgix.net/website/images/embed_chat.png)

**URL:**
```
https://embed.theta.tv/e/chat/{channel_alias}?partner={partner_id}
```




----
# JS SDK
Coming Soon.

