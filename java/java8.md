# Optional

## public static <T> Optional<T> of(T value)

代码中一共出现了三个T，第一个是定义泛型的意思，第二个是返回的类型，第三个是参数的类型，这三个类型可以说是由参数的类型来决定的。



https://zhuanlan.zhihu.com/p/579947845



# Consumer（消费型），Supplier（供给型）、[Predicate](https://so.csdn.net/so/search?q=Predicate&spm=1001.2101.3001.7020)（判断型）与Function（转换型）

## consumer

- Consumer接口是一个消费型的接口，只要实现它的accept方法，就能作为消费者来输出信息。
- lambda、方法引用都可以是一个Consumer类型，因此他们可以作为forEach的参数，用来协助Stream输出信息。
- Consumer还有很多变种，例如IntConsumer、DoubleConsumer与LongConsumer等，归根结底，这些变种其实只是指定了Consumer中的泛型而已，方法上并无变化



## supplier

- Supplier是一个供给型的接口，其中的get方法用于返回一个值。
- Supplier也有很多的变种，例如IntSupplier、LongSupplier与BooleanSupplier等



## predicate

- Predicate是一个判断型的接口，用一个test方法去测试传入的参数。
- 当然，Predicate也有对应的变种。

## function

- Function是一个转换型的接口，其中的apply可以将一种类型的数据转化成另外一种类型的数据。
- Function的变种就更多了

https://blog.csdn.net/qq_33591903/article/details/102948344

# 实体类的区别

## BO，VO，DTO，Dao

https://zhuanlan.zhihu.com/p/102389552



# lambda表达式

https://blog.csdn.net/qq_33591903/article/details/102896536
