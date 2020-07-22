# AntiVM

根据[博文](https://msq01.github.io/2020/07-21-%E5%8F%8D%E6%B2%99%E7%AE%B1%E8%99%9A%E6%8B%9F%E6%9C%BA%E6%8A%80%E6%9C%AF/)中提到的反虚拟化示例进行的测试

使用下面几个API遍历设备信息，判断是否为VMware

```
SetupDiGetClassDevs
SetupDiEnumDeviceInfo
SetupDiGetDeviceRegistryProperty
SetupDiDestroyDeviceInfoList
```
