bayesian_ab
======

**bayesian_ab** is a javascript library for A/B-testing 


### Usage ###

```javascript
var bayesian_ab = require("bayesian_ab");
// collect impression and donation counts
var rate_data= {
    'A' : {'num_donations': 500, 'num_impressions': 1000},
    'B' : {'num_donations': 488, 'num_impressions': 1000},
    'C' : {'num_donations': 480, 'num_impressions': 1000}
}
results = bayesian_ab.rate_comparison(rate_data)
return results
```

### Building from source ###

To download the package and install the development dependencies run ```npm install git://github.com/hanslemm/bayesian_ab.git```

### License ###

bayesian_ab is distributed under the [MIT License](http://www.opensource.org/licenses/MIT).
