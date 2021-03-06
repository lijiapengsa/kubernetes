# kubernetes实践

### 基本步骤流程：

- [x] <a href="etcd/README.md">etcd</a>
- [x] <a href="flannel/README.md">flannel</a>
- [x] Kubernetes集群
  - [x] <a href="k8s-install-tls/gen-ca/README.md">生成证书</a>
  - [x] <a href="k8s-install-tls/README.md">部署Master节点</a>
  - [x] <a href="k8s-install-tls/README.md">部署Node节点</a>
- [x] dns
  - [ ] ~~<a href="doc/kube-dns/README.md">kube-dns</a>~~已经弃用
  - [x] <a href="doc/coredns/README.md">coredns</a>
- [x] <a href="doc/dashboard/README.md">dashboard</a>
- [ ] <a href="doc/metrics-server/README.md">metrics-server</a>
- [x] <a href="doc/helm/README.md">helm</a>
- [x] <a href="doc/prometheus/README.md">prometheus</a>
  - [x] <a href="doc/prometheus/README.md">grafana</a>
- [ ] ingress
  - [x] <a href="doc/ingress/README.md">nginx</a>
  - [ ] treafik
- [ ] <a href="./doc/hpa/README.md">HPA</a>
  - [ ] <a href="./doc/hpa/HPA实践.md">Horizontal Pod Autoscaler实践</a>
- [ ] 存储
  - [ ] nfs
  - [ ] ceph
  - [ ] ...
- [ ] 服务网格
  - [ ] Istio
  - [ ] ...
- [ ] Weave Scope （一种监控工具）
- [ ] 未完待续

遗留问题:

kubelet 启动和kubeconfig的关系。

#### 各组件原理和操作文档请参考`/doc`目录下内容，和各目录下README.md

------

不要止步于此。仔细研究各个组件的基本原理、这样才会更上一层楼。

------

kubernetes集群之上的各种基础服务的描述文件都在源码里面点击[链接直达](https://github.com/kubernetes/kubernetes/tree/master/cluster/addons)

------

官方文档：https://kubernetes.io/docs/tasks/tools/install-kubectl/

官方中文：https://kubernetes.io/cn/docs/concepts/cluster-administration/certificates/

Dashboard官方部署文档：https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/

中文翻译：http://docs.kubernetes.org.cn/

个人教程：https://github.com/sadlar/k8s-install-note

个人教程：https://github.com/gjmzj/kubeasz

kubernetes监控架构：https://github.com/kubernetes/community/blob/master/contributors/design-proposals/instrumentation/monitoring_architecture.md

阿里云服务：https://help.aliyun.com/document_detail/53751.html?spm=a2c4g.11186623.6.561.avRpWN



