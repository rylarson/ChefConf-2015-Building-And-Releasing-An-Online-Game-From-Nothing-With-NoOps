# ChefConf-2015-Building-And-Releasing-An-Online-Game-From-Nothing-With-NoOps

NoOps (Doesn't mean there is no operations)
  Means there is no dedicated operations people (NoOps for Tripwire!)

Problem: 20 people trying to make an abitious online game.

Erlang/OTP, what the heck is that

"Programming Erlang by Joel Armstrong"

Elixir, programming language that is build on the Erlang VM. Good tooling, "One part Ruby, one part Clojure, one part Erlang".

Built with Lein. 

Ask BenG/Chris about this

Elixir's syntax makes Erlang and the ecosystem much more approachable.

Elixir has Mix, a build tool that ships with the language.
Hex is the package manager/dependency resolver
True modern language

!! Application Engineer Owns the cookbooks for their application. //This is just like the application developer owning the unit tests and test automation.

Consul for auto service discovery (HashiCorp)

Discovery is for discovering Erlang nodes. Erlang nodes are fully meshed but don't scale past 100 nodes.

githead.com/undeadlabs/discovery

Discovery (written in Elixir). (Poller, PollerEvent, Handler, Heartbeat)

Terraform. It is very stable now. Use it to describe infrastructure. You can do everything you can with the AWS console but you can do it in a programatic way.

!! Application engineers own and Maintain their Terraform module as well.

TODO Show this recorded talk as a dev working group

Remote state storage in a provider:
  Atlas/Consul

Clone undeadlabs/cloud-environments.git
has the Terraform templates.

Using terraform with AWS
airpair.com/aws/posts/inteiered-aws-docker-terraform

github.com/reset

Client gets state from the server and the server is authoritative about that state. 

Jamie still uses the Environment Cookbook Pattern

TODO Do movies on all of Jamies talks, he is fantastic.

