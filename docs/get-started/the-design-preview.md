---
id: the-design-preview
title: The Design Preview
---

On this page, you will explore the attributes of the window; and then use some of them to adjust the size of the window when it is shown in the preview pane.

Examine the XAML for the `<Window>` tag. It will look like this:

```xml
<Window xmlns="https://github.com/avaloniaui"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        mc:Ignorable="d" d:DesignWidth="400" d:DesignHeight="550"
        x:Class="GetStartedApp.MainWindow"
        Title="GetStartedApp">
```

The window tag starts by defining some of the XML namespaces that _Avalonia UI_ uses. The aliases 'x', 'd' and 'mc' are used.

The design namespace 'd' allows the design-time attributes `d:DesignWidth` and `d:DesignHeight`to be set. In the above code sample, these have been set to make the preview look more like a mobile (portrait orientation) display. 

With these attributes set, the preview of the window now looks like this:

<div style={{textAlign: 'center'}}>
    <img src="/img/get-started/the-design-preview/image (64).png" alt="" />
</div>

On the next page, you will see how to add some action to the app by responding to the button click event. 