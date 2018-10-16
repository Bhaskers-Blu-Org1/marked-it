# Change Log

This project uses [semantic versioning](http://semver.org/).

##[0.10.5] 2018-10-16
Changes to support setting a custom path prefix in TOCs generated by marked-it-cli.

##[0.10.4] 2018-10-11
Fixed path adjustment bug in JSON TOC adapter.

##[0.10.3] 2018-09-26
A generated document's title is now determined by the first `H1` or `H2` that's encountered.

##[0.10.2] 2018-08-13
Bug fixes.

##[0.10.1] 2018-08-13
Changes to support JSON-format TOC generation by marked-it-cli.

##[0.10.0] 2018-08-02  
### New features
Support has been added for generating TOCs in JSON format.  To use this, specify option `tocJSON: true` when invoking `generate()`, and the JSON TOC output will be included in the result's `jsonToc` field.

##[0.9.0] 2017-12-21  
Events sent from the following extension points now include a *src* attribute that contains the original markdown source of the new element:
- html.onCode
- html.onHeading
- html.onHr
- html.onHtml
- html.onParagraph
- html.onTable

##[0.8.0] 2017-05-07  
Initial release