# 远程私有库

- 1、创建远程私有库GitHub，码云， 此为cocoapods的索引库 <https://github.com/qinlaoban/QRFMBaseSpec>
- 2、本地常见pod 库
  - pod repo add QRFMBase git@github.com:qinlaoban/QRFMBaseSpec.git
- 创建本地spec文件 
  - pod lib create xxx
    - 修改spec文件
  - pod lib lint

- git init、add 、commit
- git remote add origin <https://gsithub.com/qinlaoban/QRFMBaseSpec.git>
- git push --set-upstream origin master
- -git push --tags