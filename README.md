# 展览导览漏斗与分时容量调整

展览资料包含合成的预约、扫码、讲解和离场事件，保留展项、场次和校准版本。

项目中的记录和字段约定均为本地合成资料，不能代表真实个人、机构或交易。`fixtures/schema.json` 说明资料字段，`fixtures/records.json` 提供少量可复现的交接记录。

使用 Node.js 22.23.4。首次准备可执行 `npm ci --ignore-scripts --offline`，检查资料使用 `npm run check:materials`，运行构建检查使用 `npm run build`，运行测试使用 `npm test`。项目只依赖 Node.js 标准库。

## 业务资料

fixtures/domain-materials.json 收录场馆声环境统计的并行使用限制与排班所需的字段约定和小型演练记录。资料由人工构造，只供本地复现，不含真实人员或机构记录。

使用 Node.js 22.23.4。执行 npm test 检查资料结构，执行 npm run build 检查项目脚本，执行 npm run check:materials 检查通用资料读取入口。
