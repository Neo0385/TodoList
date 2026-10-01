# TodoList
First practice project by HTML,CSS and Vue3,FastAPI.  

---  

组件库（手写 CSS 夯实基础），逐阶段引入新技术。

目录组织（Monorepo 单仓结构）：  

todo-fullstack/  
├── frontend/ # 前端代码（阶段一至四）  
├── backend/ # 后端代码（阶段五至六创建）  
├── .gitignore  
└── README.md
  
Git 分支演进架构： main (主分支) ─────────────────────────────────────────► 最终合并全栈生产版  
│  
├─► feat-vanilla-js(阶段一/二: HTML5 + CSS3 + 原生 DOM + LocalStorage + Mock API)  
│    
└─► feat-vue3 (阶段三/四: Vite + Vue 3 核心 + Vue Router + Pinia + Axios)  
│  
└─►feat-fastapi(阶段五/六:FastAPI + SQLite+JWT 鉴权 +零成本/服务器部署)   

---  


## 阶段一
### Task1 
- 项目初始化 + Git骨架。  
  目标：  
  建立一个本地 Git 仓库，关联到 GitHub 远程仓库，把基线文件提交到 main，再切出 feat-vanilla-js 作为阶段一工作分支。本任务不写任何 HTML/CSS，纯 Git 骨架。

### Task2
- HTML5 语义结构。  
  目标：  
  用纯 HTML 写出 TodoList 的静态骨架。不写 CSS，不写 JS。做完以后在浏览器打开，应该看到的是：一堆没有任何样式的、从上到下排布的内容——黑字白底、方方正正的输入框和按钮、列表前面有小圆点。这就是对的。  
重点：input, button, 

为什么故意不加样式：这一节要专心练“结构”和“语义”。等 Task 3 再上 CSS 时，你会清晰地看到“样式是给结构穿衣服”，而不是“结构和样式混在一起抄”。

### Task 3.1  
- Grid 2D 概念 + 现代工具链（本轮，纯讲）  
重点：Grid,

### Task 3.2  
- Grid 宏观骨架：:root 变量 + 页面切割 + 调试色

### Task 3.3  
- Flexbox 1D 局部排版：表单行、任务项对齐

### Task 3.4  
- 细节收尾：状态样式、圆角阴影、gap 调距

### Task 3.5  
- Task 3 结业考核（诊断 + 变式重考）
