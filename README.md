# fastHtml

<!-- bmc:front -->
<p align="center"><a href="https://buymeacoffee.com/dayongfan"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&amp;emoji=&amp;slug=dayongfan&amp;button_colour=FFDD00&amp;font_colour=000000&amp;font_family=Cookie&amp;outline_colour=000000&amp;coffee_colour=ffffff" alt="Buy me a coffee"></a></p>
<!-- /bmc:front -->

一个简单的psd直接导出html的工具

自己工作常用整理

**适合单页面且采用DOM结构布局的H5页面，基于Canvas的H5请使用Flash2x+AnnieJS!**

**导出前的准备**

先对psd里图层做整理，文字要栅格化图层，图层也要栅格化，剪切蒙版也要格式化掉，只保留基本图层和分组结构

**使用**

``cnpm install //安装包 ``

``npm start {psd文件路径} //文件路径，必须指定！ 如：npm start 001.psd``

<!-- bmc:middle -->
<p align="center"><a href="https://buymeacoffee.com/dayongfan"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&amp;emoji=&amp;slug=dayongfan&amp;button_colour=FFDD00&amp;font_colour=000000&amp;font_family=Cookie&amp;outline_colour=000000&amp;coffee_colour=ffffff" alt="Buy me a coffee"></a></p>
<!-- /bmc:middle -->

**目录说明**

—lib/	//解析psd的脚本，核心部分

—export/	//导出目录

—tmp.html	//生成的HTML结构模板文件，此为基础结构

—package.json	//包json文件，npm install 安装

**特点**

所有div元素的定位采用rem，适配更多浏览器

根据psd文件名生成单独的目录，不会互相覆盖

独立的HTML结构，方便多个单页整合到一起

感谢：

 https://github.com/meltingice/psd.js ，此为核心

<!-- bmc:end -->
<p align="center"><a href="https://buymeacoffee.com/dayongfan"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&amp;emoji=&amp;slug=dayongfan&amp;button_colour=FFDD00&amp;font_colour=000000&amp;font_family=Cookie&amp;outline_colour=000000&amp;coffee_colour=ffffff" alt="Buy me a coffee"></a></p>
<!-- /bmc:end -->
