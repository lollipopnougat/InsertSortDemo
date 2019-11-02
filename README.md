# SortDemo

排序算法演示 `TypeScript` 实现<br>
[GitHub托管的静态页面](https://lollipopnougat.github.io/SortDemo/)


### 设计模式

采用了策略模式，将排序算法封装，对外采用统一的接口

## 注意

* 请确保安装了 `nodejs` 和 `npm`
* 使用了 `TypeScript`<br>
  全局安装
  ```
  npm i -g typescript
  ```
* 使用了 `Less`<br>
  全局安装
  ```
  npm i -g less
  ```
* 使用了 `jquery`
* 直插排序和希尔排序的动画有待改进

## 修改了项目如何编译

1. 克隆项目后，然后在项目下打开终端，执行
    ```
    npm i
    ```

2. 修改了 `less` 或者 `ts` 源码以后，需要执行
    ```
    npm run compile
    ```

3. 然后执行 (也可以不执行这句，直接开html也可以观看)
    ```
    npm start
    ```
    打开浏览器，定位到 http://localhost:8080 即可看到页面


## 待实现算法:

* <del>直接插入排序 (InsertSort)</del>
* <del>希尔排序 (ShellSort)</del>
* <del>冒泡排序 (BubbleSort)</del>
* 快速排序 (QuickSort)
* <del>简单选择排序 (SelectSort)</del>
* 堆排序 (HeapSort)
* 归并排序 (MergeSort)

