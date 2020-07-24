从spring源码中学习到的知识点：

1. srping common 包中： StringUtils.tokenizeToStringArray("123,2.34", ",."); 
2. logger.isDebugEnabled() 使用该参数可以提高性能，如果直接使用logger.debug("xxx")会花时间构造参数，当在高并发时可能会影响性能。
3. BeanUtils.instantiateClass(xxx.class);
4. Steam.of(数组): 数组转Steam

