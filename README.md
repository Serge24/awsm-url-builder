# Awesome Url Builder!
Minimalist package to help you build awesome url. Below are installation instructions and examples
 
 
# Installation
| yarn  | npm |
|--|--|
| yarn add awsm-url-builder | npm i awsm-url-builder |

# Examples
**Example N°1**

    const  urlBuilder = require("awsm-url-builder")
    const  path = urlBuilder("http://example.com/:param1/:param2", {
	    param1: "me",
	    param2: "test"
    });
    console.log(path) //==> http://example.com/me/test

**Example N°2**

    const  urlBuilder = require("awsm-url-builder")
    const  path = urlBuilder("http://e-market.com/:{product_slug}/info", {
    	product_slug: "compass",
    });
    console.log(path) //==> http://e-market.com/compass/info
