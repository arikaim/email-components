## Arikaim CMS email components library
![version: 1.0.0](https://img.shields.io/github/release/arikaim/email-components.svg)
![license: GPL3](https://img.shields.io/badge/License-GPLv3-blue.svg)

Arikaim CMS email components library.


#### Requirements   
  * [Arikaim CMS](https://github.com/arikaim/arikaim)


#### Installation

```sh
composer require arikaim/email-components
```

#### Example usage

Email template code: 
```
    {{  component('email~foundation.button',{ 
            class:'rounded',
            title: 'Click', 
            url: 'Link Url' 
        },'static') 
    }}

```