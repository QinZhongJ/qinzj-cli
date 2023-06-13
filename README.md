# qinzj-cli
常用框架脚手架

## 安装

### 全局安装
```bash
npm install -g qinzj-cli
```
# or yarn
```bash
yarn global add qinzj-cli
```

### 使用
创建模版
```bash
qinzj-cli create <name> [-t|--template]
```
示例
```bash
qinzj-cli create hello-cli -t dumi2-demo
```

### 不全局安装，借助npx
创建模版
```bash
npx qinzj-cli create <name> [-t|--template]
```
示例
```bash
npx qinzj-cli create hello-cli -template dumi2-demo
```