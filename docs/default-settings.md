# SceneWish 各入口默认设置（as of 2026-11-03）

> 记录 [SceneWish](https://scenewish.com/) 公开页面上各生成入口打开时的默认模型与参数，方便对比。数据为 2026-11-03 未登录访问所见，之后可能调整，以页面为准。

| 入口 | 必填输入 | 默认模型 | 默认参数 |
|---|---|---|---|
| [首页创作框](https://scenewish.com/) | 文字描述；起始帧可选 | Seedance 1.0 Pro Fast | 16:9 · 5s · 480p，6 credits |
| [Image to Video](https://scenewish.com/image-to-video) | 起始帧（必填）+ 动作描述 | Seedance 1.0 Pro Fast | 16:9 · 5s · 480p |
| [First & Last Frame](https://scenewish.com/first-last-frame-to-video) | 首帧 + 尾帧 + 变化描述 | Seedance 2.0 Fast | 16:9 · 5s · 480p |
| [Reference to Video](https://scenewish.com/reference-to-video) | 至少 1 张参考图（最多 7）+ 新场景描述 | Kling v3 Omni | 16:9 · 5s · 720p |
| [AI Crying 模板](https://scenewish.com/templates/ai-crying) | 1 张正脸成人肖像 | 模板预设 | 9:16 或 16:9 · 5s · 720p · 无声 |

## 共同点

- 文字描述上限 4000 字符。
- 打开示例或模板只会预填输入，**按下 Generate 之前不会生成、不会扣点**；点数报价显示在 Generate 旁。
- 上传图片支持“My images”素材库复用。

## 换模型时注意

- 参考图上限因模型而异：例如 Seedance 2.5 可到 30 张，Veo 3.1 Fast 为 1–3 张且固定 8 秒。
- 首尾帧入口的模型都只接受 2 张图，差别在时长、分辨率和是否跟随原图比例。

---
作者为 SceneWish 团队成员（运营方：扬帆AI中国有限公司）。请只使用自己拥有或已获授权的素材，分享时注明 AI 生成。
