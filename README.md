#Test
to 色凯：
数据库表admin：
CREATE TABLE `admin` (
  `Aid` int(32) unsigned NOT NULL AUTO_INCREMENT COMMENT '管理员序号',
  `Aname` varchar(256) CHARACTER SET utf8 NOT NULL COMMENT '管理员用户名',
  `Apd` varchar(256) CHARACTER SET utf8 NOT NULL COMMENT '管理员密码',
  PRIMARY KEY (`Aid`,`Aname`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
