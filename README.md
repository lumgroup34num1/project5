# project5 Impl Merkle Tree following RFC6962
## 1、实验原理
Merkle Tree即哈希树，本质上是一个哈希列表，在此基础上引入了树形结构，灵活性更强。  
Mercle Tree的叶子结点是数据块的hash值，非叶子结点是其对应子节点串联字符串的hash。
## 2、实验结果
### 创建10w叶子结点的merkle tree
![image](https://github.com/lumgroup34num1/project5/assets/129478488/cfe0da19-c167-4e59-8022-b8e561b76392)
### 存在性证明
![image](https://github.com/lumgroup34num1/project5/assets/129478488/2d6cb9e5-d921-40e9-8d9f-21cf7817cac0)
### 不存在证明
![image](https://github.com/lumgroup34num1/project5/assets/129478488/f708c300-ef4f-4ec2-ba31-74e0ea0d5e67)
![image](https://github.com/lumgroup34num1/project5/assets/129478488/26d5c775-332b-49d4-8fed-c9df04c44d78)
