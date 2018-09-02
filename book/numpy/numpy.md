### 1.numpy生成数组的多种方式
- 把列表转换为数组
    ```
    np.array([1, 2, 3, 4, 5])
    ```
- 把元组转换成数组
    ```
    np.array((1, 2, 3, 4, 5))
    ```
- 把range对象转换成数组
    ```
    np.array(range(5))
    ```
- 多维数组
    ```
    np.array([[1, 2, 3], [4, 5, 6]])
    ```
- 指定取值范围的数组
    ```
    np.arange(8)
    np.arange(1, 10, 2)
    ```
- 初始值是0的数组
    ```
    np.zeros(5) 一维数组
    np.zeros([5，5]) 二维数组
    ```
- 初始值是1的数组
    ```
    np.ones(5) 一维数组
    np.ones([5，5]) 二维数组
    ```
- 等差数组
    ```
    np.linspace(start, end, step)
    ```
- 空数组，只申请空间而不初始化，元素值是不确定的
    ```
    np.empty((3,3))
    ```
- 随机数组
    ```
    np.random.randint(0, 50, [5,10，3])
    np.random.rand(val,[num])
    ```
- 从标准正态分布中随机采样
    ```
    np.random.standard_normal(5)
    np.random.normal(loc=0,scale=1,size=5)
    ```
- 类似单位矩阵数组
   ```
   np.identity(3)
   ```
- 类似对角矩阵数组
    ```
    np.diag([1,2,3])
    ```

