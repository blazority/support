# Blazority
> This a public repository to receive incoming issues, feedback, and feature request from Blazority community.


-----

![Blazor Icon](https://img.stackshare.io/service/8436/BrandBlazor_nohalo_1000x.png) ![Clarity UI Icon](https://img.stackshare.io/service/7683/PLsb-YNy_400x400.jpg)

[![Gitter](https://badges.gitter.im/blazority/support.svg)](https://gitter.im/blazority/support?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
![GitHub](https://img.shields.io/github/license/karan-kang/blazority-public)


Blazority is a Blazor component library based on [Clarity UI](https://clarity.design/). Our aim is to provide components that are easy to use, and built as purely as possibly using Blazor, with little to no JavaScript (less than 1KB). This libary is compatiable with both Blazor Server and Web Assembly modes.

# Demos
Visit [https://blazority.com/](https://blazority.com/) for most up-to-date demos and usage docs.

# Getting Started

[Install Blazority using Nuget](https://www.nuget.org/packages/Blazority/) or Package Manager Console: 
```
Install-Package Blazority
```

Add the using block for Blazority in your _Imports.razor file:
```
@using Blazority
```

Add the following stylesheets in the head section of your Index file (like _Host.cshtml):

```
<link rel="stylesheet" href="_content/Blazority/lib/clr/ui/clr-ui.min.css" />
<link rel="stylesheet" href="_content/Blazority/lib/clr/icons/clr-icons.min.css" />
<link rel="stylesheet" href="_content/Blazority/blazority.min.css" />
```

Add the following scripts in the bottom portion of body tag in the same Index file:
```
<script src="_content/Blazority/lib/webcomponents/custom-elements/custom-elements.min.js"></script>
<script src="_content/Blazority/lib/clr/icons/clr-icons.min.js"></script>
<script src="_content/Blazority/blazority.min.js"></script>
```

