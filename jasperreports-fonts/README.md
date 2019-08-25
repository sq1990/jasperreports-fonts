# jasperreports-fonts
JasperReports字体库扩展，针对最新的JasperReports解决导出PDF时中文乱码的问题


Sample Reports Fonts
=============================

Some of the supplied samples use the TrueType font files found in the 
/demo/fonts directory. In order to run those samples you should install 
these fonts into your operating system so that they are available to the JVM. 
The procedure required to install fonts depends on the operating system. 
On Windows systems this is equivalent to copying the font files into 
the <WINDOWS>\Fonts directory.

注意添加字体需要是*.ttf，windows自带字体是*.ttc，直接修改后缀不好用

1. 将*.ttf添加到/net/sf/jasperreports/fonts/dejavu/下
2. 修改fonts.xml，添加新加字体