### InternStudio开发机创建与环境搭建

![1.1](./picture/1.1.png)

### InternStudio环境获取模型

![1.2](./picture/1.2.png)

### LMDeploy验证启动模型文件

![1.3](./picture/1.3.png)

此时的现存为：

![1.4](./picture/1.4.png)

### 2.1 LMDeploy API部署InternLM2.5

![1.5](./picture/1.5.png)

![1.6](./picture/1.6.png)

![1.7](./picture/1.7.png)

![1.8](./picture/1.8.png)

#### 以Gradio网页形式连接API服务器

![1.9](./picture/1.9.png)

### **设置最大kv cache缓存大小**

![1.10](./picture/1.10.png)

###  设置**在线** kv cache int4/int8 量化

![1.11](./picture/1.11.png)

### 2.2.3 W4A16 模型量化和部署

![1.12](./picture/1.12.png)

![1.13](./picture/1.13.png)

![1.14](./picture/1.14.png)

![1.15](./picture/1.15.png)

![1.16](./picture/1.16.png)

![1.17](./picture/1.17.png)

### 2.2.4 W4A16 量化+ KV cache+KV cache 量化并模型封装本地API并与大模型进行一次对话

![1.18](./picture/1.18.png)

### 此时的显存占用情况

![1.19](./picture/1.19.png)