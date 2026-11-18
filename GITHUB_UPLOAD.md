# GitHub 上传说明

本项目可作为已完成基础流程的回归学习项目展示。当前模型未超过简单参考，目标统计周期和原始数据再分发许可尚未确认；这些局限已在 README 中保留。

## 应使用哪个文件夹

使用本次检查生成的 `sales-prediction-demo-github-*.zip`，先解压，再打开里面的 `sales-prediction-demo` 文件夹。发布副本的 Notebook 已清除运行输出和执行编号，避免把输出里的商品明细、链接带入仓库。

本地学习项目保留完整运行输出和数据。发布副本保留代码、README、依赖清单、数据获取说明、两张图和四张指标/重要性汇总CSV。

## 网页上传步骤

1. 在你选择的 GitHub 仓库中打开 **Add file → Upload files**。
2. 上传解压后 `sales-prediction-demo` 文件夹内的文件和子目录，保留 `data/`、`img/`、`results/` 的结构，让 `README.md` 位于仓库根目录。
3. 确认没有 `data.xlsx`、`sales_cleaned.csv`、`test_predictions.csv`、`.venv`、`.env` 或 `.ipynb_checkpoints`。
4. 核对 Notebook 的代码格输出为空，填写提交说明，例如 `Add ecommerce regression learning project`，再提交。
5. 在仓库首页检查 README 是否显示、两张图是否加载。需要运行实验的人先按照 `data/README.md` 获取数据，再安装依赖并运行 Notebook。

ZIP 是分发包；要让仓库展示源码和README，应上传解压后的内容。原始数据未随包提供，下载代码后需要自行取得数据，才能完整重跑实验。

本次没有替你选择源码开源许可证。公开展示代码与授权他人使用代码是不同决定，后续可按你的选择添加合适的许可证；数据许可仍独立遵循来源要求。

上传界面和文件限制以 [GitHub 官方添加文件说明](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)为准。本次任务只检查和打包，没有执行远程上传。
