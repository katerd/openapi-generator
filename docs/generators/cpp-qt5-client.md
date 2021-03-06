---
title: Config Options for cpp-qt5-client
sidebar_label: cpp-qt5-client
---

| Option | Description | Values | Default |
| ------ | ----------- | ------ | ------- |
|sortParamsByRequiredFlag|Sort method arguments to place required parameters before optional parameters.| |true|
|sortModelPropertiesByRequiredFlag|Sort model properties to place required parameters before optional parameters.| |true|
|ensureUniqueParams|Whether to ensure parameter names are unique in an operation (rename parameters that are not).| |true|
|allowUnicodeIdentifiers|boolean, toggles whether unicode identifiers are allowed in names or not, default is false| |false|
|prependFormOrBodyParameters|Add form or body parameters to the beginning of the parameter list.| |false|
|cppNamespace|C++ namespace (convention: name::space::for::api).| |OpenAPI|
|modelNamePrefix|Prefix that will be prepended to all model names.| |OAI|
|optionalProjectFile|Generate client.pri.| |true|
