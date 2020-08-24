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
