One ring to rule them all, or, how many layers of abstration do you need until we can all talk esparanto?

Is an open source devops possible?

Terraform might provide enough layers of abstration to account for provisioning with puppet, ansible, and chef.

When you start a new develoment project you select a technology based on the intended outcome and the resources that can be brought to bear to execute the design and form that point on everyon has to work within the confines of the selected linguistic ocnditions.  Fedora is a java project, archivesspace is a ruby/jruby project, and if you are going to contribute you have to work within the ocnfines of the language.

DevOps doesn't work like this.
Local political conditions, market forces and personal prejudice based on experience all have their say before a "devops technology is selected".


You must be able to run the same set up procedures and end up with the same set of runtime conditions on vagrant, bare metal, on prem virtual solutions or cloud based solutions (aws, azure, google, rackspace, ...); and all platforms should be able to be combined with any of th configuration management systems (puppet, chef, ansible, ?)

Installation must be generalizable, repeatable, standardized (i.e. packaged) and idempotent.

the fedora and archivesspace developers communities all share a common language

I woulnd't try to popose a single standard, rather I'd like to try and outline a workign methodology that might lead towards the possibility of the standardization of practice.  ok, ok, that's all a bit lofty, a better way to describe this is this is how I do things

single source vagrant

Minimal shell provisioners

everything installed from puppet

build from the ground up.

