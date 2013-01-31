Mockista
========
Concept: Rails Generator for design mocks 
```Cucumber
Feature: 
  As a Designer 
  In order to get a head start on the developers
  I want to mock functioning pages without rails yelling at me 
  So that the developers can have styled html/css when they start a story
```


rails g mockista:install
```
  - created 'app/mocks' directory
```
rails g mocista:mock Cat
```
  - created 'apps/mocks/cat'
```

vim app/mocks/cat
```YAML
#----------------------------------------
Thing: Cat

Fields:
  - color
  - mood #grumpy of course

Pages:
  #defaults:
  #new:     /cats/new
  #show:    /cats/update
  #edit:    /cats/edit
  #create:  /cats/create
  #destroy: /cats/destroy

#------------------------------------------
```
