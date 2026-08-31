# fzu-ics

福州大学教务系统课表日历导出工具。

## 使用

```bash
go run main.go
```

支持通过环境变量指定参数，未设置时交互式输入：

| 环境变量 | 说明 |
| --- | --- |
| `FZU_ID` | 学号 |
| `FZU_PASSWORD` | 教务系统密码 |
| `FZU_TERM` | 学期（`all` 或具体学期） |
| `FZU_OUTPUT` | 输出文件名，默认 `福州大学课程表 [学号] (学期).ics` |

## Author

**fzu-ics** © Baoshuo, Released under the [GPL-3.0](./LICENSE) License.<br>
Authored and maintained by Baoshuo.

> [Personal Website](https://baoshuo.ren) · [Blog](https://blog.baoshuo.ren) · GitHub [@renbaoshuo](https://github.com/renbaoshuo)
