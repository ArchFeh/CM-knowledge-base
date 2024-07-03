# 外部贡献者协议比较

### CLA和DCO区别

CLA，全称是 [Contributor License Agreement](https://en.wikipedia.org/wiki/Contributor_License_Agreement)，简单来说就是项目在接收 contributor 贡献的补丁之前，需要 contributor 签署的一份协议。这是一份法律协议。通常，如果贡献构成小代码贡献，则不需要 CLA。

DCO，全称 [Developer Certificate Of Origin](https://elinux.org/Developer_Certificate_Of_Origin) 是一种开源贡献者证明其拥有提交代码的权利并同意按照项目的许可证发布它的声明。DCO 通常用作[贡献者许可协议](https://en.wikipedia.org/wiki/Contributor_License_Agreement "Contributor License Agreement") （CLA） 的替代方案。DCO 不是签署的法律合同，而是确认某个人确认是他或她对发送代码的行为承担法律责任，这使得在任何法律诉讼的情况下更容易将责任转移给代码发送者，从而阻止发送任何可能导致法律问题的代码。


| 特性         | CLA                                                | DCO                                                        |
| ------------ | -------------------------------------------------- | ---------------------------------------------------------- |
| 社区属性     | 弱                                                 | 强                                                         |
| 签署方式     | 一次性                                             | 每次提交时在 commit 信息里追加 `Signed-off-by: email` 信息 |
| 法律责任     | 明确法律义务                                       | 无声明，用来限制提交者遵守开源 license                     |
| 是否可自定义 | 公司或组织可自行定义                               | 否                                                         |
| 使用案例     | Google、Pivotal、CNCF、阿里巴巴、Apache SkyWalking | GitLab、Chef、Harbor、TiKV                                 |
| 公司属性     | 强，可以签署公司级别的 CLA                         | 弱                                                         |
| 实施方案     | 用户下载pdf签名回传邮件/建立网页进行在线签名       | 每次提交时在 commit 信息里追加 `Signed-off-by: email` 信息 |

# 建议

- 如果开源项目可能会有公司间合作或者要贡献给基金会，为了防范法律风险，使用 CLA；
- 如果更看重社区内的合作，可以使用 DCO。
