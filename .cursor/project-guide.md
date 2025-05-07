shadcn-admin/
├── src/                           # 源代码目录
│   ├── assets/                    # 静态资源文件
│   ├── components/                # 组件目录
│   │   ├── ui/                    # 基础UI组件
│   │   ├── layout/                # 布局组件
│   │   ├── command-menu.tsx       # 命令菜单组件
│   │   ├── confirm-dialog.tsx     # 确认对话框组件
│   │   ├── password-input.tsx     # 密码输入组件
│   │   ├── profile-dropdown.tsx   # 用户资料下拉菜单
│   │   ├── search.tsx            # 搜索组件
│   │   └── theme-switch.tsx      # 主题切换组件
│   │
│   ├── features/                  # 功能模块目录
│   │   ├── auth/                  # 认证相关功能
│   │   ├── dashboard/            # 仪表盘功能
│   │   ├── users/                # 用户管理功能
│   │   ├── tasks/                # 任务管理功能
│   │   ├── settings/             # 设置功能
│   │   ├── chats/                # 聊天功能
│   │   └── apps/                 # 应用管理功能
│   │
│   ├── routes/                    # 路由配置
│   ├── stores/                    # 状态管理
│   ├── hooks/                     # 自定义React Hooks
│   ├── utils/                     # 工具函数
│   ├── lib/                       # 核心库和配置
│   ├── context/                   # React上下文
│   ├── config/                    # 应用配置
│   ├── main.tsx                   # 应用入口文件
│   └── routeTree.gen.ts           # 生成的路由树
│
├── public/                        # 公共静态资源
├── .github/                       # GitHub配置
├── .cursor/                       # Cursor IDE配置
│   └── rules/                     # Cursor规则文件
│
├── package.json                   # 项目依赖和脚本
├── vite.config.ts                 # Vite配置
├── tsconfig.json                  # TypeScript配置
├── components.json                # shadcn/ui组件配置
├── eslint.config.js              # ESLint配置
├── .prettierrc                    # Prettier配置