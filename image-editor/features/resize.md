---
title: Resize
page_title: Resize
description: Resize
slug: radimageeditor-resize
tags: image, editor, resize 
published: True
position: 0
---

# Resize using the UI

You can use the __Resize__ button which will open the resize dialog. The resize dialog where you can enter the desired size.

![](images/image-editor-resize002.png)
![](images/image-editor-resize001.png)


# Resize Programmatically

You can resize an image that is loaded inside the image editor with code as well. This can be achieved with the Resize method. The following snippet demonstrates this.

#### Resize Programmatically

{{source=..\SamplesCS\ImageEditor\ImageEditorFeatures.cs region=Resize}} 
{{source=..\SamplesVB\ImageEditor\ImageEditorFeatures.vb region=Resize}}
````C#
radIamgeEditor1.ImageEditorElement.Resize(500, 500);

````
````VB.NET
```` 


{{endregion}}
 