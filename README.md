# dubbotrave
给dubbo扩展filter方法
1.注释
@Activate(group = Constants.CONSUMER)
并添加aop依赖
2.在如下目录下添加对应filter的文本信息
resources
 META-INF.dubbo
  com.alibaba.dubbo.rpc.Filter
     traceFilters=com.alibaba.dubbo.filter.DrpcCientFilter
     
可将标签删除，此方法为网站上提供的方法，经尝试无效
<dubbo:consumer filter="xxxFilter" />


