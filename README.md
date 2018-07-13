[![Build Status](https://travis-ci.org/chrisesharp/scoreboard-service.svg?branch=master)](https://travis-ci.org/chrisesharp/scoreboard-service)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/81212ba902b34f80b54b806a1968e196)](https://www.codacy.com/app/chrisesharp/scoreboard-service?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=chrisesharp/scoreboard-service&amp;utm_campaign=Badge_Grade)
# scoreboard Service

## Build

Perform a Maven and Docker build with:
```
make
```

## Test

Verify the service still honours its `pact` with:
```
make test
```

## Run

Run locally under Docker with:
```
make run-keystore
```
This will mount the keystore volume you will need to have created using:
https://github.com/chrisesharp/shared-keystore 

Run under Kubernetes in Docker for Mac with Helm installed:
```
make install
```

## Clean Up

Clean up build artifacts with:
```
make clean
```

