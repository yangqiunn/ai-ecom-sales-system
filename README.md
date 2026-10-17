# 智能云AI电商在线销售系统

> 根据《智能云AI电商在线销售系统》成果包实现的电商在线销售系统（静态网站版），已通过 GitHub Pages 完成外网发布。

## 🌐 在线访问

**发布地址**：见仓库 Settings → Pages 显示的 URL（形如 `https://<用户名>.github.io/ai-ecom-sales-system/`）

## 🔑 登录信息

| 项目 | 值 |
|------|-----|
| 账号 | `admin` |
| 密码 | `admin123` |

## ✅ 功能清单

- **登录认证**：账号密码校验（admin / admin123），会话内免登录，错误提示
- **商品展示**：8 件在售商品（名称/描述/现价/原价/标签/已售量）
- **购物车**：加入、增减数量、删除、小计与合计实时计算（localStorage 持久化）
- **订单提交**：生成订单号、明细清单、应付金额，订单数据本地留存并统计
- **外网发布**：GitHub Pages 静态托管，HTTPS 访问

## 🛠 技术说明

- 纯 HTML / CSS / JavaScript 单页应用，**零依赖、零构建**
- 状态持久化：`localStorage`（购物车、订单）+ `sessionStorage`（登录会话）
- 响应式布局，支持移动端访问

## 📦 本地运行

直接双击 `index.html` 即可在浏览器打开，或：

```bash
python3 -m http.server 8080
# 访问 http://localhost:8080
```
