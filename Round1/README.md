# Round 1 介绍

1、以的日期为key,以每天的访问记录为value ，输出为日期+访问记录
2、 map以日期+页面为key，访问记录为value，reduce以访问量为key，日期+页面为value
3、map以日期+页面为key，不同IP  访问次数为value，reduce以前一天访问后次日再次访问了的IP为key，日期+页面为value
