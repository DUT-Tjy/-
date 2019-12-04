## 垃圾邮件分类任务
### DUTIR主页评测任务
DUTIR在线评测平台：[http://ir.dlut.edu.cn/](http://ir.dlut.edu.cn/)
### 执行步骤
1、百度网盘下载数据集解压到当前文件夹（包含train、test、index.txt）

2、从ipython notebook中进入到当前文件夹，q全部执行data_preprocess.ipynb，生成预处理文件（处理语料缺失，结果保存在csv文件中）

3、本人采用bert进行向量化处理，输入到GBDT中（部分代码可见keras-practice仓库），提交结果为result.txt