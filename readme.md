# UABEa Enhanced

基于 [UABEa](https://github.com/nesrak1/UABEA) 的二次开发版本，增加了批量处理 MonoBehaviour 的功能，方便 Unity 资源分析与快速操作。

## 功能特点

- 保留原 UABEa 功能完整性  
- **新增功能：**
  - **批量导出 MonoBehaviour**：一次性导出多个资源中的 MonoBehaviour 数据，方便分析与备份  
  - **批量导入 MonoBehaviour**：一次性导入修改后的 MonoBehaviour 数据，支持快速还原或修改游戏资源  

## 安装

1. release界面下载压缩包
2. 按照原 UABEa 的说明运行即可  
3. 新增功能位于工具栏 `自定义功能` 菜单下  

## 使用说明

### 批量导出 MonoBehaviour

1. 打开 Unity AssetBundle 或 `.assets` 文件  
2. 点击 **批量导出 MonoBehaviour**  
3. 选择保存路径，即可生成多个 JSON

### 批量导入 MonoBehaviour

1. 准备好修改后的 MonoBehaviour 文件  
2. 打开对应的资源文件  
3. 点击 **批量导入 MonoBehaviour**  
4. 选择文件夹或多个文件，程序会自动替换对应的资源  

## 更新记录

### v1.0.0 (2025-08-28)
- 新增批量导出 MonoBehaviour 功能  
- 新增批量导入 MonoBehaviour 功能  


## License

遵循原 UABEa 授权协议。
