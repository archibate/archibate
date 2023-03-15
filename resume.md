| 个人 | 简历 |
|------|-------|
| 姓名 | 彭于斌 |
| 电话 | 17721388340 |
| 微信 | tanh233 |
| 邮箱 | 1931127624@qq.com |
| GitHub | https://github.com/archibate |
| 就读院校 | 上海建桥学院-软件工程-大四 |
| 求职意向 | C++开发/软件工程师 |
| 爱好特长 | 图形学/操作系统 |
| 出生年月 | 2001.08 |
| 政治面貌 | 群众 |
| 学历 | 本科 |

热爱并投身于开源事业，熟练运用 Git 和 GitHub，与其他同事分工合作。能够 review 他人的 pull request，指出代码中的 BUG，严格代码规范。

- 目前在泽森科工有限公司主导研发基于节点的图形引擎 Zeno（[zenustech/zeno](https://github.com/zenustech/zeno)），由于学校需要，人在上海，上课的空闲时间远程办公，研发 Zeno，我们的官方网站: http://zenustech.com
- [Zeno 早期版本中](https://github.com/zenustech/zeno/tree/zeno_old_stable) 为本人自行用 PyQt5 编写的节点编辑器，调用同样为本人自研的后端节点执行引擎，后来转型到 C++ Qt 前端转手交给其他同事负责。
- 早期版本采用 pybind11 从 Python 调用 C++，[当前版本](https://github.com/zenustech/zeno) 改为 Python 作为可选的扩展插件语言，Python 端通过 ctypes 直接调用 Zeno C API。

熟练运用 C++17 和部分 C++20 新特性，熟悉 RAII 内存管理和内存安全，能够运用现代 C++ 写出安全的代码。学习能力强，很快就能掌握新知识，常看 CppCon，能运用元编程思想在 C++ 中开发可复用的程序组件，会用现代 CMake 构建程序。具有分享精神，乐于帮他人解决编程中遇到的各种疑难杂症，擅长用幽默风趣的语言，教会他人新知识。

- 制作了 C++ 编程系列公开课《高性能并行编程与优化》（parallel101/course），目前更新到第 16 集，录播可在[比站免费观看](https://www.bilibili.com/video/BV1V84y117YU)，广受同学好评。内容涵盖并行计算（包括 TBB 和 CUDA），现代 C++ 特性，C++11 多线程编程，内存模型，SIMD 优化等。对性能优化有一定经验，了解 CPU 和 GPU 的物理结构，理解缓存局域性对性能的[影响](https://www.bilibili.com/video/BV1gu41117bW)。

爱好计算机图形学，熟悉 OpenGL 和 CUDA，会写 compute shader，目前也有学习 Vulkan 的打算。

- 在 Zeno 中实现了基于 OptiX 的光线追踪的离线渲染后端，和基于 OpenGL 的实时渲染后端，渲染结果在编辑器 viewport 中实时可视化（lookdev），viewport 中支持点击选中物体，拉动摇杆进行拖动，旋转，缩放等。
- 曾在快手把 Taichi 移植到安卓平台，导出 Taichi Kernel 为 shader 资产，并编写安卓客户端 SDK 从 Java 调用 OpenGL ES 使用 Taichi 的 shader，实现二维特效动画，如用户对着摄像头流眼泪，眼泪在屏幕形成水池，基于 SPH 进行流体仿真，同时会根据用户手机的重力感应影响流体等效果。
- 曾成功把 Zeno 移植到安卓平台，在手机上成功运行手指滑动水面效果。

学过 GAMES101 课程，对渲染领域基本功了如指掌。

- 自研基于 Taichi 的实时软光栅渲染器（[taichi-dev/taichi_three](https://github.com/taichi-dev/taichi_three)），其 Python API 允许以类似节点的形式设置材质，支持 PBR 贴图，法线贴图，天空盒照明（IBL）。可以加载 OBJ，GLTF 模型/场景，能在 OpenGL，CUDA，CPU 等多种后端上运行。支持了一系列屏幕空间特效如 SSAO，SSR，SSGI 等，包括多种抗锯齿算法如 TAA，MSAA，FXAA 等，支持 ACES tonemapping 以便在 LDR 设备上显示，并添加 blooming 效果。附带基于体素 marching cube 的粒子云重建为 mesh 网格功能。
- 自研基于 Taichi 的离线渲染器（[archibate/ptina](https://github.com/archibate/ptina)），基于 BVH 的路径追踪算法，支持渲染三角形网格和体积雾。实现了多重重要性采样，迪士尼 BRDF（每个属性都支持贴图），实现了 Metropolis 采样，也支持 Light-tracing 用于渲染焦散效果。支持多光源，meshlight，天空盒照明。渲染收敛速度快，和 Blender 内置的 Cycles 渲染结果比对发现相差无几，而且基于 CUDA 比 Cycles 快很多。
- 早期在 Shadertoy 上用 GLSL 编写过一些渲染测试：https://www.shadertoy.com/user/archibate

熟悉 Python 语法，会写 PyTest 测试。

- 参与 Taichi，一种图形特效方面的领域特定语言（[taichi-dev/taichi](https://github.com/taichi-dev/taichi)），可以把前端简单易懂的 Python 代码，JIT 编译成多种后端（包括 CPU，OpenGL，CUDA，Vulkan，Metal，DX 等），实现跨平台与生产力的兼得。
- 为 Taichi 编写仿 GLSL 的数学库（[taichi-dev/taichi_glsl](https://github.com/taichi-dev/taichi_glsl)），实现矢量运算，双/三线性插值等图形学常用功能。
- 为 Taichi 编写了 [OpenGL compute shader 后端](https://github.com/taichi-dev/taichi/pulls?q=opengl)，性能和 CUDA 后端相差无几，在用到了 float atomicAdd 的 mpm 案例上甚至优于 CUDA 后端，因为 yuanming 写的 CUDA 后端是 CAS 实现的。
- 为 Taichi 编写了 [OpenCL 后端](https://github.com/taichi-dev/taichi/pull/495)，但由于 yuanming-hu 个人忙于毕业论文的原因，最后直到我退出太极时都没有合并。

长期在 Linux 环境中开发，熟悉命令行的使用，能够编写 Python / Bash 脚本自动化一些日常文本处理任务，由于剪辑课程录播需要学会了 ffmpeg 的命令行用法。

喜欢用 JS + HTML5 Canvas 实现一些能在线运行的仿真 demo。

- 编写基于 Flask 的 Web 服务 Taichi.js（taichi-dev/taichi.js），前端基于 MDUI 开发，用户在浏览器中点击“运行”提交 Python 脚本，后端调用 Taichi 的 C 后端生成 C99 代码，然后在配置好的 Docker 容器中调用 Emscripten 编译成 WASM（带缓存）传回前端浏览器中高效运行流体仿真等算法，并在 HTML5 Canvas 上实时渲染。
- 自研二维刚体物理引擎 newton.js（[archibate/newton](https://github.com/archibate/newton)），支持添加约束/边界等，在线预览效果：https://archibate.github.io/newton
- 基于 Flask 的 Web 服务，同网段下方便地在手机和电脑之间传输文件（archibate/qrcparchibate/qrcp）
- 用 docsify 编写 Zeno 项目文档（[zenustech/zeno-docs](https://github.com/zenustech/zeno-docs)），目前已转手交给其他员工维护。

我擅长制作 Blender 插件，熟悉 Blender 的 Python API，必要时还会通过 pybind11 调用 C++ 中的高性能代码，通过 NumPy 数组高效地在 Python 和 C++ 之间传递大规模数据。

- 纯 Python 实现的 Blender 插件（[taichi-dev/taichi_blend](https://github.com/taichi-dev/taichi_blend)），并加入了上面提到的两款渲染器
- Python 和 C++ 混合编写的 Blender 插件（[zenustech/zeno](https://github.com/zenustech/zeno)），把 Zeno 项目集成到 Blender，用 Blender 节点编辑器创建 Zeno 节点，类似于几何节点，对模型进行处理后输出到 Blender 对象上

对操作系统和编译原理有一定理解，编写过若干个可运行的操作系统和编译器。

- Unix-like 的宏内核操作系统（[archibate/newos](https://github.com/archibate/newos)），实现了部分 c 标准库函数，支持 Copy-on-Write 的 fork 系统调用。支持 /dev 虚拟文件系统，能够运行自己编写的 sh，vi（实现了 IO 多路复用），贪吃蛇等程序，全部封装成了单独一个类似于 busybox 的可执行文件。
- 模仿 seL4 的微内核操作系统（[archibate/chaos](https://github.com/archibate/chaos)），系统函数完全基于 IPC。
- 通过 /dev/uinput 注册虚拟设备，实现键盘映射到手柄（archibate/key2joy）
- 在 Zeno 中实现了 ZFX 模块，根据用户输入的 DSL 代码，JIT 编译生成 SIMD 二进制，执行并行的高性能浮点运算。

学过 GAMES201 物理仿真专题课程，会用 C++/CUDA 编写高性能高精度物理仿真程序。

- 太阳系行星多体引力 RK4 仿真程序（[archibate/NBodySolver](https://github.com/archibate/NBodySolver)），OpenMP 并行。能够模拟出月球轨道进动等天文学现象，预测日食达到 10′ 精度。
- 基于 CUDA 的三维 LBM 卡门涡街仿真（[archibate/cuda_aero_lbm](https://github.com/archibate/cuda_aero_lbm)）
- 基于 OpenGL compute shader 的 MPM 软体仿真（[archibate/opengl_mpm](https://github.com/archibate/opengl_mpm)）

使用 Lua 语言编写过一些游戏模组。

- 为《以撒的结合》制作了一系列功能性模组，并上传到 [Steam 创意工坊](https://steamcommunity.com/id/archibate/myworkshopfiles/?appid=250900)，广受玩家好评。
- 我个人自用的 [NeoVim 配置](https://github.com/archibate/vimrc/tree/nvim)

其他项目。

- 基于 JSP 的象棋在线对战系统（[archibate/jsp-chess](https://github.com/archibate/jsp-chess)），MySQL 数据库，Docker 部署，支持人人对战核人机对战。
- 人脸识别实验项目（[archibate/facereco](https://github.com/archibate/facereco)），后来用于互联网应用大赛的“云课堂”考试时的人脸检测，防止学生代考作弊。
