# SpringCloudConfigDemo
SpringCloudConfigServerDemo

配置中心测试


### 配置规则
Spring Cloud Config 有它的一套访问规则，我们通过这套规则在浏览器上直接访问就可以。

/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties
