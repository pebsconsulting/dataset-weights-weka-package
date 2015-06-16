dataset-weights-weka-package
============================

Weka package with filters that allow modifying attribute/instance weights.

The following filters are available:
* `weka.filters.unsupervised.attribute.ModifyAttributeWeights`
* `weka.filters.unsupervised.instance.ModifyInstanceWeights`

Available modifiers for *attribute* weights:
* `FixedValue` - applies the user-specified weight to selected range of attributes  
* `FromFile` - uses the weights stored in a file
* `PassThrough` - dummy, does nothing

Available modifiers for *instance* weights:
* `FixedValue` - applies the user-specified weight to selected range of rows  
* `FromAttribute` - uses the values from a numeric attribute as weights
* `FromFile` - uses the weights stored in a file
* `PassThrough` - dummy, does nothing

