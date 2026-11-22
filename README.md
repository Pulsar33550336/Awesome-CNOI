# Awesome CNOI

面向中文 OI 社区的软件索引：收录 OIer 常用的软件，以及为 OI 开发的工具、平台与服务。

完整规范见 [SPEC.md](SPEC.md)。

## 写代码

- [Atom](https://atom.io/) — GitHub 开发的可扩展编辑器，已停止维护。 `app` `gui` `general-purpose` `MIT` `discontinued`
- [cf-tool](https://github.com/xalanq/cf-tool) — Codeforces 的命令行客户端，可拉题、跑样例与提交。 `app` `cli` `oi-specific` `MIT` `archived`
- [Clang](https://clang.llvm.org/) — LLVM 的 C/C++ 编译器前端。 `app` `cli` `general-purpose` `Apache-2.0` `active`
- [clang-format](https://clang.llvm.org/docs/ClangFormat.html) — Clang 的代码格式化工具，按配置统一缩进与换行。 `app` `cli` `general-purpose` `Apache-2.0` `active`
- [clangd](https://clangd.llvm.org/) — 基于 Clang 的语言服务器，为编辑器提供补全、跳转与诊断。 `app` `cli` `general-purpose` `Apache-2.0` `active`
- [CLion](https://www.jetbrains.com/clion/) — JetBrains 的跨平台 C/C++ IDE，自带调试器、补全与重构。 `app` `gui` `general-purpose` `Unfree` `active`
- [Code::Blocks](https://codeblocks.org/) — 轻量的 C/C++ IDE，资源占用少，启动快。 `app` `gui` `general-purpose` `GPL-3.0` `maintained`
- [CP Editor](https://cpeditor.org/) — 为算法竞赛设计的编辑器，支持自动编译运行、抓取样例并直接提交。 `app` `gui` `oi-specific` `GPL-3.0` `active`
- [CPH](https://github.com/agrawal-d/cph) — VS Code 扩展，在编辑器内编译运行并对着样例判题。 `app` `ide-plugin` `oi-specific` `GPL-3.0` `active`
- [CPH-NG](https://github.com/langningchen/cph-ng) — CPH 的下一代，在 VS Code 内编译运行、判样例并提交。 `app` `ide-plugin` `oi-specific` `AGPL-3.0` `active`
- [Dev-C++](https://www.embarcadero.com/free-tools/dev-cpp) — Windows 上常见的 C/C++ IDE，安装便捷，支持单文件编译。 `app` `platform-only(windows)` `gui` `general-purpose` `GPL-2.0` `maintained`
- [Eclipse](https://www.eclipse.org/) — 集成开发环境平台，功能可通过插件扩展。 `app` `gui` `general-purpose` `EPL-2.0` `active`
- [Emacs](https://www.gnu.org/software/emacs/) — 以 Emacs Lisp 扩展的文本编辑器，内置终端、邮件与文件管理。 `app` `tui` `gui` `general-purpose` `GPL-3.0` `active`
- [GCC](https://gcc.gnu.org/) — GNU 编译器集合，常用其中的 C++ 编译器 `g++`。 `app` `cli` `general-purpose` `GPL-3.0` `active`
- [Geany](https://geany.org/) — 轻量的跨平台文本编辑器。 `app` `gui` `general-purpose` `GPL-2.0` `active`
- [GUIDE](https://www.noi.cn/) — 北航为 NOI 选手开发的 C/C++/Pascal 小型 IDE。 `app` `gui` `oi-specific` `Unfree` `discontinued`
- [Kate](https://kate-editor.org/) — KDE 出品的跨平台文本编辑器，支持 LSP 补全与内嵌终端。 `app` `gui` `general-purpose` `LGPL-2.1-only` `active`
- [MinGW-w64](https://www.mingw-w64.org/) — Windows 版 GCC 工具链，提供 g++ 与运行库，供 Dev-C++ 等 IDE 编译。 `app` `cli` `library` `general-purpose` `ZPL-2.1` `active`
- [Notepad++](https://notepad-plus-plus.org/) — Windows 上的轻量文本编辑器，打开大文件稳定且体积小。 `app` `platform-only(windows)` `gui` `general-purpose` `GPL-3.0` `active`
- [Sublime Text](https://www.sublimetext.com/) — 轻量的跨平台文本编辑器，启动快并支持扩展。 `app` `gui` `general-purpose` `Unfree` `active`
- [Vim](https://www.vim.org/) — 基于 TUI 的文本编辑器，以模式化键位完成编辑与跳转。 `app` `tui` `general-purpose` `Vim` `active`
- [VS Code](https://code.visualstudio.com/) — 微软开发的跨平台代码编辑器，可扩展性极强。 `app` `gui` `general-purpose` `Unfree` `active`
- [vscode-luogu](https://github.com/yltx/vscode-luogu) — VS Code 的洛谷扩展，可在编辑器内拉题、测样例与提交。 `app` `ide-plugin` `oi-specific` `MIT` `active`
- [WSL](https://learn.microsoft.com/windows/wsl/) — 在 Windows 上运行 Linux 环境，用来对齐 Linux 的编译与运行行为。 `app` `cli` `general-purpose` `Unfree` `active`
- [Xcode](https://developer.apple.com/xcode/) — macOS 上的集成开发环境。 `app` `platform-only(macos)` `gui` `general-purpose` `Unfree` `active`
- [小熊猫 Dev-C++](https://github.com/royqh1979/RedPanda-CPP) — Dev-C++ 的衍生分支，保留原界面，并集成了智能提示与较新的 MinGW。 `app` `platform-only(windows, linux)` `gui` `general-purpose` `GPL-3.0` `active`

## 练题

- [AtCoder](https://atcoder.jp/) — 日本的竞赛平台，提供 ABC、ARC 等系列比赛。 `web` `gui` `general-purpose` `Unfree` `active`
- [Codeforces](https://codeforces.com/) — 俄罗斯的竞赛平台，提供常规比赛、rating 与题解。 `web` `gui` `general-purpose` `Unfree` `active`
- [CPRet](https://cpret.online/) — 用自然语言描述题意，在题库中检索相似的题目。 `web` `gui` `general-purpose` `Unfree` `active`
- [LOJ](https://loj.ac/) — 在线评测平台，提供题库与比赛。 `web` `gui` `oi-specific` `Unfree` `active`
- [OJHunt](https://ojhunt.com/) — 跨 OJ 汇总一个账号的做题数与提交记录。 `web` `gui` `general-purpose` `BSD-2-Clause` `active`
- [QOJ](https://qoj.ac/) — 在线评测平台，收录国内外比赛题并提供自建比赛。 `web` `gui` `oi-specific` `Unfree` `active`
- [UOJ](https://uoj.ac/) — 在线评测平台，提供题库与比赛。 `web` `gui` `oi-specific` `Unfree` `active`
- [VJudge](https://vjudge.net/) — 虚拟评测平台，用同一套界面把代码提交到多个 OJ。 `web` `gui` `general-purpose` `Unfree` `active`
- [yuantiji](https://yuantiji.ac/) — 给一段题面，判断这道题是不是已有的原题。 `web` `gui` `oi-specific` `Unfree` `active`
- [洛谷](https://www.luogu.com.cn/) — 面向中文 OI 的在线评测平台，提供题库、题单与比赛。 `web` `gui` `oi-specific` `Unfree` `active`

## 出题

- [CNOI-Statement-Generator](https://cnoi.mrpython.top/) — 按 CNOI 格式排版题面的工具，从 Markdown 生成 PDF。 `app` `cli` `oi-specific` `AGPL-3.0` `active`
- [cplib](https://cplib.aberter0x3f.top/) — 单头文件 C++ 库，用来写 checker、validator 与数据生成器。 `library` `oi-specific` `LGPL-3.0` `active`
- [Hull](https://hull.aberter0x3f.top/) — Nix 驱动的出题框架，把题面、数据、判题与打包串成一条构建管线。 `app` `cli` `oi-specific` `LGPL-3.0` `active`
- [Polygon](https://polygon.codeforces.com/) — Codeforces 的多人协作出题平台，覆盖题面、数据、标程与打包。 `web` `gui` `oi-specific` `Unfree` `active`
- [Testlib](https://github.com/MikeMirzayanov/testlib) — 单头文件的出题辅助库，用来写 generator、validator 与 checker。 `library` `oi-specific` `MIT` `active`
- [Tuack](https://gitee.com/mulab/oi_tools) — 面向出题人的题目制作工具，管理题面、数据与题目打包。 `app` `cli` `oi-specific` `GPL-3.0` `maintained`
- [Tuack-NG](https://github.com/tuackng/tuack-ng) — 一套辅助 OI/ICPC 出题的工具包，旨在帮助出题人以更加便携的方式协作出题。 `app` `cli` `oi-specific` `AGPL-3.0` `active`

## 判题

- [Arbiter](https://www.noi.cn/) — 北航为 NOI Linux 开发的评测工具，随 NOI 系列比赛下发。 `app` `platform-only(linux)` `gui` `oi-specific` `Unfree` `maintained`
- [CCR Plus](https://github.com/sxyzccr/CCR-Plus) — 跨平台的测评环境。 `app` `gui` `oi-specific` `GPL-3.0` `maintained`
- [Cena](https://github.com/oi-archive/cena) — Windows 上的本地评测工具，可批量评测测试点并统计成绩。 `app` `platform-only(windows)` `gui` `oi-specific` `GPL-2.0` `discontinued`
- [Lemon](https://github.com/zhipeng-jia/project-lemon) — 本地评测系统，可对整套题目批量评测并统计成绩。 `app` `gui` `oi-specific` `Unfree` `discontinued`
- [LemonLime](https://project-lemonlime.github.io/Project_LemonLime/) — 基于 Lemon 与 LemonPlus 重写的本地评测系统，可对整套题目批量评测并统计成绩。 `app` `gui` `oi-specific` `GPL-3.0` `active`
- [LemonPlus](https://github.com/Dust1404/Project_LemonPlus) — Lemon 的改进分支，可对整套题目批量评测并统计成绩。 `app` `platform-only(windows, linux)` `gui` `oi-specific` `GPL-3.0` `discontinued`

## 杂项

- [autocorrect](https://github.com/huacnlee/autocorrect) — 文本检查工具，修正中英文混排的标点与空格。 `app` `cli` `general-purpose` `MIT` `active`
- [CF Cheater Database](https://cf-cheater-database.vercel.app/) — 记录 Codeforces 上被判作弊账号的查询库。 `web` `gui` `oi-specific` `Unfree` `unknown`
- [CS Academy 图论编辑器](https://csacademy.com/app/graph_editor/) — 在线图论编辑器，在图形与边列表之间互相转换。 `web` `gui` `general-purpose` `Unfree` `unknown`
- [Excalidraw](https://excalidraw.com/) — 手绘风格的白板，用来画示意图与讲解图，也可以当作草稿本。 `web` `gui` `general-purpose` `MIT` `active`
