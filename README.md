1. 直接选中项目，点击enter，修改项目名称
<img width="271" alt="PinjamMudah" src="https://github.com/Junetaurus/rename/assets/13435427/bbf89da5-8e66-40bd-85af-39284a6fb743">

2. 关闭项目，找到xx.xcodeproj，显示包内容，打开project.pbxproj，全局查找（contain）并替换
<img width="240" alt="project pbxproj" src="https://github.com/Junetaurus/rename/assets/13435427/a1f5e229-54aa-4789-b602-c60cc02b720c">

3. 修改对应文件名称 
<img width="256" alt="Gemfile" src="https://github.com/Junetaurus/rename/assets/13435427/7a7a9da1-6195-41da-91b4-524fe295270d">

4. 删除cocoapods相关，删除 xx.xcworkspace， Podfile.lock 并修改Podfile指定的路径，最后执行pod install 
<img width="251" alt="PinjamMudah" src="https://github.com/Junetaurus/rename/assets/13435427/5a815287-7291-43e6-aa31-f10b18cb67fc">

5. python脚本修改类名前缀
<https://github.com/Junetaurus/rename>

6. 如果为Swift且存在桥接文件，需要手动修改名称
<img width="251" alt="AppDelegate swift" src="https://github.com/Junetaurus/rename/assets/13435427/5c62ce5f-5584-4e8a-a74c-fc08725cfae7">
