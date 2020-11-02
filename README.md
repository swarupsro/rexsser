# rexsser
This is a burp plugin (python) that extracts keywords from response using regexes and test for reflected XSS on the target scope. Valid parameters reflected, vulnerable parameters are show in results in the rexsser extension tab.

### Regexes
 - extract all javascript 'var' names from response page
 - ...
 
### Screenshots

![img](https://i.imgur.com/7ygeBN1.jpg)

### Requirements
- Jython
- BurpSuite

### Todo

- [ ] Add Multiple regexes to extract words (Example: input elements in the page response)
- [ ] Content-Type filter
- [ ] Scope checkbox
- [ ] Process only given status-codes
- [ ] Turn off/on
