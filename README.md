# CocoaPods-Carthage
分别使用CocoaPods和Carthage集成第三方库

## 1.使用cocoaPods集成第三方库
  - 安装CocoaPods[参考官方文档](https://guides.cocoapods.org/using/getting-started.html)
  
      首先查看本地Ruby源地址```gem source -l```
      
      如果没有修改过应该显示```https://rubygems.org/```
      
      由于官方源经常连不上，在很长一段时间国内开发者都会使用[taobao的镜像](https://ruby.taobao.org/)
      
      然而现在RubyGems镜像的管理工作已经交由RubyChina负责，所以建议都修改成RubyChina的镜像
      
      ```gem sources --add https://gems.ruby-china.org/ --remove https://rubygems.org/```
      
      如果原来用的是taobao的镜像，那么修改一下
      
      ```gem sources --add https://gems.ruby-china.org/ --remove http://ruby.taobao.org/```  
      
      完成后查看一下```gem sources -l```
      
      ```*** CURRENT SOURCES ***
         https://gems.ruby-china.org
         # 请确保只有 gems.ruby-china.org```
         
         
