# Alert Filter operator

[![](https://nexus.lab.fiware.org/repository/raw/public/badges/chapters/visualization.svg)](https://www.fiware.org/developers/catalogue/)
![](https://img.shields.io/github/license/lets-fiware/fisuda-ngsi-source-operator.svg)<br/>
[![Build Status](https://travis-ci.org/lets-fiware/fisuda-ngsi-source-operator.svg?branch=develop)](https://travis-ci.org/lets-fiware/fisuda-ngsi-source-operator)
[![Coverage Status](https://coveralls.io/repos/github/lets-fiware/fisuda-ngsi-source-operator/badge.svg?branch=develop)](https://coveralls.io/github/lets-fiware/fisuda-ngsi-source-operator?branch=develop)

The Alert Filter operator is a [WireCloud operator](http://wirecloud.readthedocs.org/en/latest/) which can separate NGSI source values to 3 outputs by set threthold.

**NOTE:**
This WireCloud operator is based on [ngsi-source-operator](https://github.com/wirecloud-fiware/ngsi-source-operator)
created by CoNWeT Lab., Universidad Politecnica de Madrid and Future Internet Consulting and Development Solutions S.L..


## Build

Be sure to have installed [Node.js](http://node.js). For example, you can install it on Ubuntu and Debian running the
following commands:

```console
curl -sL https://deb.nodesource.com/setup | sudo bash -
sudo apt-get install nodejs
sudo apt-get install npm
```

Install other npm dependencies by running:

```console
npm install
```

For build the operator you need download grunt:

```console
sudo npm install -g grunt-cli
```

And now, you can use grunt:

```console
grunt
```

If everything goes well, you will find a wgt file in the `dist` folder.

## Documentation

Documentation about how to use this operator is available on the [User Guide](src/doc/userguide.md). Anyway, you can
find general information about how to use operators on the
[WireCloud's User Guide](https://wirecloud.readthedocs.io/en/stable/user_guide/) available on Read the Docs.

## Copyright and License

Copyright (c) 2020 Shunsuke KIKUCHI<br>
Copyright (c) 2019-2020 Future Internet Consulting and Development Solutions S.L.<br>
Copyright (c) 2014-2016 CoNWeT Lab., Universidad Politecnica de Madrid

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the
License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific
language governing permissions and limitations under the License.
