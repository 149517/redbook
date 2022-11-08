##  WEB 字体



1. 为什么使用web字体？

   * 需要在网页中嵌入远程字体
   * 特制的字体在网页中无法正确显示
   * 不同的操作设备显示的字体不相同

2. 字体托管服务

   * 处理相关的许可事宜，
   * 支持把字体转化为多种格式，确保字体包含正确的字符集及其优化
   * 提供高速的下载服务

3. 获取web字体的三种方式

   * 免费的字体经销商：这是一个可以下载免费字体的网站 (可能还有一些许可条件，比如对字体创建者的信赖)。比如： [Font Squirre](https://www.fontsquirrel.com/)，[dafont](http://www.dafont.com/) 和 [Everything Fonts](https://everythingfonts.com/)。
   * 收费的字体经销商：这是一个收费则字体可用的网站，例如[fonts.com](http://www.fonts.com/)或[myfonts.com](http://www.myfonts.com/)。您也可以直接从字体铸造厂中购买字体，例如[Linotype](https://www.linotype.com/)，[Monotype](http://www.monotype.com/) 或 [Exljbris](http://www.exljbris.com/)。
   * 在线字体服务：这是一个存储和为你提供字体的网站，它使整个过程更容易。更多细节见[使用在线字体服务](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Styling_text/Web_fonts#使用在线字体服务)。

4. 在代码中使用

   ```css
   @font-face {
     font-family: 'ciclefina';
     src: url('fonts/cicle_fina-webfont.eot');
       
     src: url('fonts/cicle_fina-webfont.eot?#iefix') format('embedded-opentype'),
            url('fonts/cicle_fina-webfont.woff2') format('woff2'),
            url('fonts/cicle_fina-webfont.woff') format('woff'),
            url('fonts/cicle_fina-webfont.ttf') format('truetype'),
            url('fonts/cicle_fina-webfont.svg#ciclefina') format('svg');
       
     font-weight: normal;
     font-style: normal;
   }
   
   ```

   

5. 将字体下载到本地使用

   ```css
   @font-face {
       font-family: AAWEILAIHEI-2;
       font-weight: bold;
       src: url("./fonts/AAWEILAIHEI-2.TTF");
   }
   ```

   