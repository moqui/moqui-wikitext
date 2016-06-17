# Moqui Eclipse Mylyn WikiText Tool Component

[![license](http://img.shields.io/badge/license-CC0%201.0%20Universal-blue.svg)](https://github.com/moqui/moqui-wikitext/blob/master/LICENSE.md)
[![release](http://img.shields.io/github/release/moqui/moqui-wikitext.svg)](https://github.com/moqui/moqui-wikitext/releases)

Moqui tool component for Eclipse Mylyn Wikitext to render wiki files such as confluence, mediawiki, textile, tracwiki, and twiki.

To install run (with moqui-framework):

    $ ./gradlew getComponent -Pcomponent=moqui-wikitext

This will add the component to the Moqui runtime/component directory. 

To use just install this component. The configuration for the TemplateRenderer implementations is already in place in the 
MoquiConf.xml included in this component and will be merged with the main configuration at runtime. 
