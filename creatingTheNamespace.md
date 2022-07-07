---
layout: page
title: Creating the demo Namespace
---

# Creating a Namespace
Hey! Captain Canary here again. Namespaces are one of those things that are so simple, they’re hard to understand. And since they deal with naming things… well… they can be hard. For our purposes, a namespace is a way to subdivide your cluster. They’re super useful for isolating different services that run in the same cluster. We need you to create a namespace called ‘demo’. 

Now, I promised before we’d have a choose your own adventure ⬆️↘️⬅️ style thing going here. But this is literally one instruction, so everyone type ⌨️ along!

> Remember in the pre-flight check I mentioned you'd need to be authenticated to your Kubernetes cluster? Now's when you'll need it.

Create the namespace with kubectl:
```sh
$ kubectl create namespace demo
``` 

That command should return a success message like this: 
```sh
namespace/demo created
```