#  reCAP 2023: Bringing Service Integration to Your Fingertips

## Description

This repository contains the material for the reCAP 2023 workshop called "Bringing Service Integration to Your Fingertips".

## Prerequisite

All prerequisites are provided for the tutorial, as we have prepared test users and BAS accounts for you!
Generally, what you would usually need to run this tutorial is:
- A subscription for SAP Business Application Studio (or a local VS Code installation)
- A browser, preferably Google Chrome

## Overview

The incidents management application allows customers to create incidents, processed by support team members. 
Both add comments to a conversation.
As customers are already available as `Business Partner` in the S/4 system, we do not want to manage them within our CAP application.
Instead we want to use the available Business Partner API to seamlessly connect information coming from the CAP application with data from the S/4 system.

## Exercises

- [Getting Started](exercises/0.-Getting-Started.md)
- [Exercise 1 - Import an API from SAP S/4HANA Cloud](exercises/1.-Importing-APIs.md)
- [Exercise 2 - Testing the API](exercises/2.-Local-Tests.md)
- [Exercise 3 - Delegating Requests](exercises/3.-Delegating-Requests.md)
- [Exercise 4 - Replicating Data](exercises/4.-Replicating-Data.md)
- [Summary](exercises/5.-Summary.md)

<!-- />
Comments
<!-->

## License

Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
