[![Maven Package upon a push](https://github.com/mosip/demosdk/actions/workflows/push_trigger.yml/badge.svg?branch=release-1.3.0)](https://github.com/mosip/demosdk/actions/workflows/push_trigger.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?branch=release-1.3.0&project=mosip_biometrics-util&id=mosip_demosdk&metric=alert_status)](https://sonarcloud.io/dashboard?id=mosip_demosdk)

# Demo SDK

## Overview
This library is used for demographic authentication in [ID-Authentication](https://github.com/mosip/id-authentication/tree/master/authentication). This SDK have implementations for demographic data match along with the name and address normalizations.

## Build (for developers)
The project requires JDK 21.0.3
and mvn version - 3.9.6

1. Build and install:
    ```
    $ cd demosdk
    $ mvn install -Dgpg.skip=true
    ```

## License
This project is licensed under the terms of [Mozilla Public License 2.0](LICENSE).
