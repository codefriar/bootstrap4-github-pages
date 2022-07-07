---
layout: page
title: Secrets Details
---

If you’re not feeling confident with adding secrets, no big deal. Can I tell you a secret? I had my friend Jim walk me through setting up Harness secrets. Twice.
Docker Hub Access Token

Harness needs a Docker Hub access token to publish Docker images to your account. See Docker Hub’s Manage access tokens documentation to learn how to create an access token. The token must have Read, Write and Delete permissions.

Click New Secret, then select Text.


Enter “Docker Hub Access Token” in the Secret Name field.

Enter your access token in the Secret Value field, then click Save.

MongoDB Atlas URI

The server process needs access to a MongoDB instance. You can create a free “shared” MongoDB Atlas instance on your preferred cloud host.

Ensure that the MongoDB Atlas instance is accessible from your Kubernetes cluster.

Click New Secret, then select Text.


Enter “atlasMongoDB Atlas uri” in the Secret Name field.

Enter your MongoDB Atlas URI in the Secret Value field, then click Save.

