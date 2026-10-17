# Week 05 · 单摆仿真实验（Pendulum Simulation）

## 实验者信息

| 项目 | 内容 |
| --- | --- |
| 姓名 | 熊浩军 |
| 学号 | 5904126090 |
| 周次 | 第 5 周 |
| 模块目录 | `week05_pendulum_sim/` |

> 请将 `<实验者姓名>` 与 `<学号>` 替换为真实信息后再提交基线。

## 无菌工作区就绪状态

- [x] 独立子目录已建立（位于课程主仓库根目录下，不污染其他周次模块）
- [x] 目录内仅包含本实验必需的说明文件，无第三方依赖、无构建产物、无缓存文件
- [x] 无与外部仓库的嵌套 `.git`、无子模块引用，保持纯净独立
- [x] Git 基线已锁定（`git add . && git commit -m "feat(week05): init pendulum experiment workspace"`，提交 `6631480`，分支 `master`）

## 目录约定

```
week05_pendulum_sim/
├── README.md        # 本说明文件（唯一已存在文件）
├── src/             # （待建）仿真源码
├── data/            # （待建）实验输入与输出数据
└── report/          # （待建）实验报告
```

## 实验目标（待补充）

1. 建立单摆运动的数值仿真模型（小角度近似 / 大角度非线性两种情形）。
2. 分析周期与摆长、重力加速度、初始摆角的关系。
3. 对比数值解与解析解误差，验证能量守恒。

## 环境依赖（待补充）

- Python 3.x
- numpy / matplotlib

## 后续待执行命令（Git 就绪后）

```bash
cd <课程主仓库根目录>
git add .
git commit -m "feat(week05): init pendulum experiment workspace"
```
