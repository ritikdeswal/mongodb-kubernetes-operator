This Dockerfile is a for an image which can be found
[here](https://quay.io/repository/mongodb/mongodb-kubernetes-operator-test-app)

The E2E tests use this to ensure that the secret genereted by the operator can be mounted into an application pod and
used to successfully connect with a Mongo client.