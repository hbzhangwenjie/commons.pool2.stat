# commons.pool2.stat
org.apache.commons.pool2 是apache提供的帮助构建一个池子的工具，jedis/lettcue 的连接池都用了他。这个工具类把这个池子的状态从jmx中拿出来返回为一个json，方便接入一些监控系统。
比如监控redis连接池 通过http把这个池子的状态输出
加入从jmx获取tomcat主要信息
