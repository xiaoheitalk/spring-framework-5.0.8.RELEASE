# Aware接口加载过程
https://www.iteye.com/blog/ray1205-2393362

AbstractApplicationContext.refresh->finishBeanFactoryInitialization->beanFactory.preInstantiateSingletons()->
getBean->doGetBean->getSingleton->singletonFactory.getObject()->createBean->doCreateBean->initializeBean

