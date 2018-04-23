---
title: Rotate
page_title: Rotate
description: Rotate
slug: radimageeditor-rotate
tags: image, editor, rotate 
published: True
position: 2
---


# Rotate via the UI

You can use the rotate buttons to directly rotate the image. No dialog is shown in this case.

![](images/image-editor-rotate001.png)

# Rotate Programmatically

The following spinet shows how you can access and use the __RotateFlip__ method.

#### Rotate programmatically

{{source=..\SamplesCS\ImageEditor\ImageEditorFeatures.cs region=Rotate}} 
{{source=..\SamplesVB\ImageEditor\ImageEditorFeatures.vb region=Rotate}}
````C#
radIamgeEditor1.ImageEditorElement.RotateFlip(RotateFlipType.Rotate270FlipNone);

````
````VB.NET
```` 


{{endregion}}

# See Also