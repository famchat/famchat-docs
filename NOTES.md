# FamChat

## Concepts

 * Public graph
 * Isolated (protected) subgraphs
 * Fam metaprotocol
 
## Examples

 * Curated nodelists adverts. E.g.:
 
    `/advertized-nodes`:
    
    `["irc://hostname:port/",...]`
    
 * `Accepts: text/x-fam`
 
    `{"tag":<string>,"payload":<object>,...}`

## Repo structure:

  * `/libfam/`
  * `/famd/`
  * `/famui/` -- flutter
  
  libfam includes http[s] server addressable by usual http[s] URLs, and in case of `Accepts: text/x-fam` returning a fam-json of data.

## Would be interesting to support as subprotocols and features:

 * irc
 * retroshare
 * activitypub/usual mastodon/usual pleroma/...
 * telegram-like channels
 * telegram-like groups
 * multi-node aggregations of some kind, for multiple nodes of one real person
 * WhaleBird-like hashtag feeds
 * to include subgraphs crawler into libfam - for search
 * vk-like object URLs
 * subgraphs reseed mechanisms as in i2p and more
 * libi2pd
 * ...
