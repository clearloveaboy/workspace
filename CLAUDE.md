# workspace

个人代码仓库，用于存放 Python 工具脚本、实验项目和代码片段。

## 项目结构

```
workspace/
├── scripts/         # 独立工具脚本
├── experiments/     # 实验性项目
├── lib/             # 可复用的工具库
├── requirements.txt # Python 依赖
└── pyproject.toml   # 项目配置
```

## 技术栈

- Python 3.x
- 使用 venv 管理虚拟环境

## 开发约定

- 每个脚本/项目独立在子目录中
- 公共工具函数放在 `lib/` 下
- 使用 `python -m` 方式运行模块
- test
