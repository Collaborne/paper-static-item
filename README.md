paper-static-item [![Bower version](https://badge.fury.io/bo/paper-static-item.svg)](http://badge.fury.io/bo/paper-static-item)
=========

`paper-static-item` provides a Material Design non-focusable [item with header and content](https://www.google.com/design/spec/components/lists.html). The web component is built with [Polymer 1.x](https://www.polymer-project.org).

![Screenshot](/doc/screenshot.png "Screenshot")


## Install

`bower install paper-static-item`


## `<paper-static-item>`

A component that contains a header with an icon below a content area.

```html
<paper-static-item icon="icons:favorite" header="Item 1">
  Lots of very interesting content.
</paper-static-item>
```

These properties are available for `paper-static-item`:

Property   | Type    | Description
---------- | ------- | ----------------------------
**icon**   | String  | Icon that is shown in the header row
**header** | String  | Text in the header row


## `<paper-static-item>`

A component that contains a single line with an item and content.

```html
<paper-static-icon-item icon="icons:info">
  Single line static item
</paper-static-icon-item>
```

These properties are available for `paper-static-icon-item`:

Property   | Type    | Description
---------- | ------- | ----------------------------
**icon**   | String  | Icon that is shown


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
    