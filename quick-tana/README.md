# Quick Tana

[⤓ Download Shortcut](https://github.com/psu/apple-shortcuts/raw/main/quick-tana/Quick%20Tana%20(shared%20v1.0).shortcut)

## About
Convert a single-line text input into a set of nodes, and add it to a specified target.

- Support for supertags, target nodes, fields, fields with reference value, and child nodes. 
- Token symbols can be customized. 
- Support for default target and default field. 

NB! Nodes and supertags have to be registered with id in advance. Space is a special character used to separate tokens from refular content. A token cannot contain a space. 

## Usage 
Input a single line of text, optionally including tokens. 

### Tokens
`@target` - set target node, first word.  
`#supertag` - add supertag to node.  
`field:text` - add field with text value.  
`field:reference` - add field with reference value.  
`:reference` - add default field with reference.  
`//` - splits the text and add as child nodes.  

## Roadmap 
- Convert [], [ ] and [x] to checkbox nodes. 
- Convert @reference to inline references. 
- Convert _single_ formatting to __double__
- Split text by --- to create node descriptions. 
- Image/file support. 

---

Pontus Sundén, 2024
