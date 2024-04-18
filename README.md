

### 项目名称
- **kubeasy**

### 项目描述
- `kubeasy`是一个使用Ansible来部署Kubernetes的项目。

### 项目状态
- 公共仓库
- 由`Phoebus888`维护，派生自`buxiaomo/kubeasy`
- 没有星星(stars)、观察者(watching)或分支(forks)

### 项目功能
- 通过Ansible自动化部署Kubernetes
- 支持在线和离线部署
- 支持多种云平台和架构，包括Raspberry Pi、Azure、Aliyun、AWS、GCP等
- 支持多种操作系统，包括但不限于CentOS、Ubuntu、Debian、OpenSUSE、Amazon Linux 2等

### Kubernetes版本支持
- 列出了不同Kubernetes版本对应的组件版本，如1.14.x至1.26.x，以及相应的软件包版本

### 使用方法
- 所有节点需要安装Python
- 提供了在线部署和离线部署的指南
- 用户需要根据需要修改`group_vars`目录中的参数
- 提供了如何配置清单(inventory)的示例和文档

### Kubernetes管理
- 部署(Deploy)
- 扩展(Scale)
- 更新Kubernetes配置
- 更新Kubernetes证书(Renew certificates)
- 升级Kubernetes版本(Upgrade)

### 离线安装
- 提供了四种不同的归档文件以支持离线安装
- 如果使用`kubeasy-offline-v${KUBEASY_VERSION}.tar.gz`，则需要一个部署服务器

### 已知问题
- 提到了cgroup子系统未挂载的问题，并提供了参考链接

### 相关资源
- Kubernetes下载
- Kubernetes变更日志
- Kubernetes命令行工具参考
- 列出了多种网络插件，如Calico、Canal、Flannel、Cilium等
- 提供了有关CoreDNS、证书、IPv4/IPv6双栈、验证IPv4/IPv6双栈、CoreDNS Kubernetes版本等的链接

### 项目文件
- 列出了仓库中的文件和目录，包括`.github`、`group_vars`、`inventory`、`plugins`、`roles`、`scripts`、`tests`等
- 提供了每个文件的最后提交信息和日期

### 项目许可证
- 使用GPL-2.0许可证

### 项目活动
- 提到了最新的提交和分支信息

### 项目反馈
- 由于列表功能处于测试阶段，鼓励用户分享反馈和报告错误

### 项目链接
- 提供了项目的Gitee、Gitlab、Github和JiHulab的克隆链接

### 项目互动
- 用户可以对项目进行星标、观察或派生复制

### 项目统计信息
- 显示了项目使用的主要编程语言，包括Jinja、Shell、Python和Makefile

### 项目建议工作流
- 根据技术栈提供了Pylint和Python应用程序的配置建议

以上是根据您提供的网页内容整理的`kubeasy`项目的详尽笔记。如果需要更详细的信息或有特定的问题，请告知。
