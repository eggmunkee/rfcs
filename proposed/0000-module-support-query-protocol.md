- Feature Name: Module Support Query Protocol
- Type New Feature
- Related components: probably routing, crust, sentinel, others
- Start Date: 22-08-2015
- RFC PR: 
- Issue number: 

# Summary

In order to allow a degree of multi-centric consensus or voluntary adoption of features, 
and to enable diverse module support among small groups in SAFE network, a module support 
query protocol could be added to allow client software determinations of module and 
module/version support and user directed support/requirements configuration options.

# Motivation

An autonomous network which has only one method for upgrade, that of a complete global 
upgrade, presents issues such as what consensus rules should decide when updates are 
globally adopted, or when separate versions get cut off by common rules, leading to 
conflict and an all or nothing environment for change.

Another option to consider would be if it is possible to build forking tolerance into 
the network protocol, by a set of configurations which ultimately restrict network 
interaction by what support features are required, ways to set preferred feature versions, 
and ways to opt-out of nodes supporting insecure or destructive modules or versions.

# Detailed design

...

# Drawbacks

Why should we *not* do this?

# Alternatives

What other designs have been considered? What is the impact of not doing this?

# Unresolved questions

What parts of the design are still to be done?
