## purescript-pux-document-title

`purescript-pux-document-title` is a wrapper for Dan Abramov's [react-document-title](https://github.com/gaearon/react-document-title).

```purescript
import Pux.Html (Html)
import Pux.Html.Attributes (title)
import Pux.DocumentTitle (documentTitle)

view :: forall a. Html a
view = documentTitle [title "Title"] []
```
