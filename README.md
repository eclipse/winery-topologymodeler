# Winery Topologymodeler [![License](https://img.shields.io/badge/License-EPL%202.0-blue.svg)](https://opensource.org/licenses/EPL-2.0) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

> Angular Component for TOSCA Topology Rendering and Editing

[Winery] is a Web-based environment to graphically model TOSCA topologies and plans managing these topologies.
It is an Eclipse project and thus support is available through its project page <https://eclipse.org/winery>.
This project enables stand-alone usage of the Topology Modeling and Editing components.

The aim is to be able to offer a self-contained JSON data set to this Angular component and it renders the topology.

**The code and the linked libraries are NOT approved by Eclipse Legal.**

**There was no security of Eclipse Winery. There might be [remote code execution vulnerabilities](https://github.com/mbechler/marshalsec). Thus, when hosting Eclipse Winery, make it accessible to turstworthy parties only.**

Both development and user documentation is rendered at <https://eclipse.github.io/winery/>.

The source code documentation can be generated by running `npm run doc` which creates a [docs/](docs) folder.

## Quickstart

To run the Winery Topologymodeler, you need to
  1. Ensure that [node.js](https://nodejs.org/en/) is installed in version greater `8`
  2. Run `npm install`
  3. Run `npm start`
  4. Ensure that [Winery] is running (either locally or in a docker container)
  5. Open <http://localhost:4201> to see the loading screen
     1. If you followed the [Winery Quickstart](http://eclipse.github.io/winery/user/#quickstart), you can open
      <http://localhost:4201/?repositoryURL=http:%2F%2Flocalhost:8080%2Fwinery&uiURL=http:%2F%2Flocalhost:4200%2F%23%2F&ns=http:%2F%2Fwinery.opentosca.org%2Ftest%2Fservicetemplates%2Fponyuniverse%2Fsplittingservicetemplate&id=SplittingServiceTemplateTest>  

### Developers

As a developer please follow the guidelines provided at <http://eclipse.github.io/winery/dev/>.
Everything metioned in <http://eclipse.github.io/winery/dev/angular-ui> also applies to this project.

## Update `repositoryUiDependencies`

If there are updates required to the modal module which is based on the [Winery Repository UI](https://github.com/eclipse/winery/tree/master/org.eclipse.winery.repository.ui/src/app/wineryModalModule),
the changes **MUST** be transferred to [Winery](github.com/eclipse/winery) also.

This also applies for changes made to the `wineryModalModule` in the Winery Repository UI.


## License

Copyright (c) 2017-2018 Contributors to the Eclipse Foundation

See the NOTICE file(s) distributed with this work for additional
information regarding copyright ownership.

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0, or the Apache Software License 2.0
which is available at https://www.apache.org/licenses/LICENSE-2.0.

SPDX-License-Identifier: EPL-2.0 OR Apache-2.0

  [Winery]: https://github.com/eclipse/winery
