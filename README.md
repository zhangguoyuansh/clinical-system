## xadmin

榆次纪检

--------------20170610-------------------
1、将之后的model类放到独立的application/orm文件夹中，使用如下：
use ORM\Test;
2、自动加载，不需要运行composer dump-autoload


--------------20170609-------------------
添加model类之后需要运行以下方法
composer dump-autoload
之后刷新页面即可

