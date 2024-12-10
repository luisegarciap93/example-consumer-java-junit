# Example Java Junit Consumer

[![Build](https://github.com/pactflow/example-consumer-java-junit/actions/workflows/build.yml/badge.svg)](https://github.com/pactflow/example-consumer-java-junit/actions/workflows/build.yml)

![Can I Deploy](https://testdemo.pactflow.io/pacticipants/pactflow-example-consumer-java-junit/branches/master/latest-version/can-i-deploy/to-environment/production/badge)

This is an example of a Java consumer that uses Pact with Junit, [PactFlow](https://pactflow.io) and GitHub Actions to ensure that it is compatible with the expectations its consumers have of it.

The project uses a Makefile to simulate a very simple build pipeline with two stages - test and deploy.

It is using a public tenant on PactFlow, which you can access [here](https://test.pactflow.io) using the credentials `dXfltyFMgNOFZAxr8io9wJ37iUpY42M`/`O5AIZWxelWbLvqMd8PkAVycBJh2Psyg1`.

See the canonical consumer example here: https://github.com/pactflow/example-consumer
See also the full [PactFlow CI/CD Workshop](https://docs.pactflow.io/docs/workshops/ci-cd) for which this can be substituted in as the "consumer".

## Pre-requisites

**Software**:

https://docs.pactflow.io/docs/workshops/ci-cd/set-up-ci/prerequisites/

## Usage

```sh
make test
```
