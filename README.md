# 知识创作者的驾驶舱

**Knowledge Creator's Cockpit**

- 版本：V1.0-beta
- 日期：2026年7月3日

## 关于本仓库

本仓库为参加 IDE 产品介绍会而建立，用于存放参会资料、活动记录以及活动可能产生的后续成果。

本仓库是一个临时仓库。作者有更完整的后续作品正在准备中，将在条件成熟时另行发布。

## 文件清单

| 文件名 | 说明 |
| --- | --- |
| README.md | 本文件 |
| 创意提交文案.txt | IDE 产品介绍会提交的创意文案全文 |
| 创意提交文案.txt.asc | 对上述文件的 GPG 明文签名 |
| zhuheng.cam_public-key.asc | 作者的 GPG 公钥，供验证签名使用 |

## 签名验证

本仓库的正式文件均附有 GPG 明文签名。验证方法：

1. 下载本仓库的 `zhuheng.cam_public-key.asc`。
2. 导入公钥：

   ```bash
   gpg --import zhuheng.cam_public-key.asc
   ```

3. 验证签名：

   ```bash
   gpg --verify 创意提交文案.txt.asc
   ```

经验证通过的签名，证明该文件确由作者本人签署，且内容未被篡改。

## 作者与联系

- 作者：铸衡
- GitHub：[https://github.com/zhuheng-cam/cognitive-architect-workspace](https://github.com/zhuheng-cam/cognitive-architect-workspace)
- 联系邮箱：[zhuheng.cam@proton.md](mailto:zhuheng.cam@proton.md)

## 版本记录

- **V1.0-beta**：2026 年 7 月 3 日，首次发布。
