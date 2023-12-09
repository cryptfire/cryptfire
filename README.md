# Meet Cryptfire

Cryptfire sets up a MongoDB, Nginx, knative Cluster as well as an Admin Dashboard and a sample NextJS-Auth application. A visual tool allows you to create and manage your database schemas, collections and attributes, as well as Users and Sessions, Projects (Frontends/Apps) and Crypto integration. 

❗ Utilize [Appwrite](https://github.com/appwrite/appwrite) for highest expectations and great design while this is still in the works.

<br />

![logo](https://github.com/cryptfire/cryptfire/assets/114028070/f7c71b88-cc5d-4e90-8e36-41b73a945c0e)


## Quick start

❗ This repository is still empty as it will host our own BaaS solution. Please use [Appwrite](https://github.com/cryptfire/cryptfire-appwrite) for now.

The goal is to provide a Proof-of-concept Docker install but to guide you through the more sophisticated self-hosting installation neatly.

```bash
docker run -it --rm \
    --volume /var/run/docker.sock:/var/run/docker.sock \
    --volume "$(pwd)"/cryptfire:/usr/src/code/cryptfire:rw \
    --entrypoint="install" \
    zdanl/cryptfire:0.0.1
```

Self-hosted Engineers Installation


## Maintainers

Cryptfire is maintained and is being operated by [@zdanl](https://github.com/zdanl)

## Copyright

The code base is licensed under the GNU v3 General Public License.
