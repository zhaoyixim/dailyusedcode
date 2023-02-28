
最好直接使用 yarn upgrade-interactive --latest


第一种
// 先下载
 
yarn global add npm-check-updates
 
// 更新包（yarn.lock和package.json同步更新）
 
ncu --upgrade --upgradeAll && yarn upgrade
第二种
yarn upgrade-interactive --latest
 
// 需要手动选择升级的依赖包，按空格键选择，a 键切换所有，i 键反选选择
第三种
yarn upgrade package@version
 
// yarn.lock和package.json都会更新，但是会进行版本锁定 "echarts": "4.2.0-rc.2"