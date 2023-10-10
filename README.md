# EJP-RD-LOVD semantic model

This model is based on the
 [EJP-RD Common Data Elements (CDE) semantic model](https://github.com/ejp-rd-vp/CDE-semantic-model).
It reuses the elements related to the
 [diagnosis of rare diseases](https://github.com/ejp-rd-vp/CDE-semantic-model/blob/master/docs/Diagnosis.md)
 and the elements related to the
 [genetic diagnosis](https://github.com/ejp-rd-vp/CDE-semantic-model/blob/master/docs/Genotype.md).
Several elements have been added to allow for more LOVD data to be included.
Not all original elements are currently in use, but they are included to adhere
 to the original model.
They may be removed in the future, if it becomes clear that these won't be used
 and removal will not cause issues with compatibility with the original model.

## Validation of data files

You can validate data files in TTL format (see the
 [example file](examples/LOVD.ttl)) against the
 [ShEx schema file](schemas/v.1.0/LOVD.shex), for instance using the
 [shex.js](https://github.com/shexjs/shex.js) tool.
For an online implementation where you can directly load the example data and
 schema file, see the
 [shex-simple interface](https://shex.io/webapps/shex.js/doc/shex-simple.html?manifestURL=https://raw.githubusercontent.com/LOVDnl/EJP-RD-LOVD-model/main/.manifest.yaml).
