# dubbotrave
给dubbo扩展filter的是以下注释
@Activate(group = Constants.CONSUMER)

resources
 META-INF.dubbo
  com.alibaba.dubbo.rpc.Filter
     traceFilters=com.alibaba.dubbo.filter.DrpcCientFilter
     
可将标签删除，此方法为网站上提供的方法，经尝试无效
<dubbo:consumer filter="xxxFilter" />


