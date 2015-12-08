材料设计图标ADT模板
=========================
Android的工作室/ Eclipse的ADT模板，包括图标演示在https://www.google.com/design/icons/

![menu](menu.png "menu")
![template](template.png "template")

Setup
-----

1. Clone this repo
2. Run `git submodule update --init` in the root folder to download the material-design-icons submodule
3. Copy the MaterialDesignIcons folder to your IDE templates folder:
   - Android Studio: `<android-studio-folder>/plugins/android/lib/templates/other`
   - Eclipse: `<android-sdk-folder>/extras/templates/other`

Usage
-----

- Android Studio: Right click on your application module and select **New > Other > Material Design Icons**
- Eclipse: Right click on your project and select **New > Other... > Android > Android Object > Material Design Icons**
Using a font collection

所述iconfont文件夹包含预生成可包含在一个项目中的字体文件。这是为在网络特别方便;然而，通常最好链接到托管在谷歌字体的Web字体:

<link href="https://font.c2cmalls.com/icon?family=Material+Icons" rel="stylesheet">
详情请阅读我们的全力开发指南的字体部分。
Thanks
------

Based on https://github.com/jgilfelt/androidicons-adt-template

License
-------

    Copyright 2014 readyState Software Limited
    Copyright 2014 Michael Basil

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
