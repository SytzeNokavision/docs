---
title: "File manager"
parent: "file-widgets"
tags: ["studio pro"]
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

{{% alert type="warning" %}}The file manager widget is not supported on native mobile pages.{{% /alert %}}

A file manager is used to upload and/or download files.

{{% alert type="info" %}}

![](attachments/pages/file-manager.png)

{{% /alert %}}

It must be placed inside a data view connected to the entity System.FileDocument or a specialization thereof.

## General properties

### Type

This property indicates how the end user can interact with the file manager.

| Value | Description |
| --- | --- |
| Upload | The file manager can only be used to upload a file. |
| Download | The file manager can only be used to download a file. |
| Both | The file manager can be used to upload, and to download a file. |

_Default value:_ Both

### Max file size (MB)

This property determines the maximum size of files (in megabytes) that can be uploaded.

_Default value:_ 5

### Allowed extensions

You can specify the file extensions that are allowed to be uploaded. If no extensions are specified all file extensions are allowed. Separate multiple extensions by a semi-colon, e.g. `txt;doc`

If a file with an extension that is not allowed is selected, a system text (File manager > Incorrect file extension) will be shown underneath the file manager.

### Show file in browser

This property indicates whether the file will be shown in the browser, instead of being downloaded.

_Default value:_ False

{{% snippet file="refguide/label-property.md" %}}

## Editability properties

{{% snippet file="refguide/editable-property.md" %}}

{{% snippet file="refguide/condition-property.md" %}}

## Visibility properties

{{% snippet file="refguide/visibility-property.md" %}}

{{% snippet file="refguide/visibility-property-with-module-roles-simple.md" %}}

## Common properties

{{% snippet file="refguide/name-property.md" %}}

{{% snippet file="refguide/class-property.md" %}}

{{% snippet file="refguide/style-property.md" %}}

{{% snippet file="refguide/tab-index-property.md" %}}

## Related articles

*   [Data view](data-view)
*   [Entities](entities)
*   [Associations](associations)
