# WenKang

[English](README.md)

南开大学研三学生。我的技术能力主要来自自学和项目实践，方向包括数据工程、软件系统、Web 协议、计算研究工具与 Agent runtime。

我更喜欢把一次性的困难探索，整理成可以测试、解释和长期维护的小系统。

## 平台数据项目

- **[TripAdvisor 猫途鹰酒店评论爬虫](https://github.com/wwk990630/tripadvisor-hotel-review-data-scraper)**：结构感知评论解析、分页保护、隐私最小化断点，以及完整的多阶段研究历程。
- **[Expedia 智游网酒店评论爬虫](https://github.com/wwk990630/expedia-hotel-review-data-scraper)**：GraphQL 响应解析，并明确区分 Akamai/传输证据与数据标准化。
- **[Airbnb 爱彼迎房源爬虫](https://github.com/wwk990630/airbnb-listing-data-scraper)**：递归提取嵌入式房源状态，按 ID 去重，并对结构变化显式报错。
- **[Yelp 商户评论爬虫](https://github.com/wwk990630/yelp-review-data-scraper)**：评论边标准化与隐私最小化分页诊断，只保留状态而不保存游标值。
- **[Agoda 安可达酒店评论爬虫](https://github.com/wwk990630/agoda-hotel-review-data-scraper)**：评论响应包验证，以及十分制到五分制的显式量表转换。
- **[Booking.com 缤客酒店数据爬虫](https://github.com/wwk990630/booking-com-hotel-data-scraper)**：面向爬虫协议研究的 challenge 状态机与校验实验，清楚标注证据边界。

六个仓库都可以独立安装，提供中英文文档、离线测试和人工夹具。

## 其他项目

- **[国内旅游平台方法研究](https://github.com/wwk990630/china-travel-platform-research)**：携程与途家的文档型协议研究，不公开可直接运行的采集代码。
- **[科研分析网站](https://github.com/wwk990630/wwk-analysis-app)**：从真实科研使用中持续改进，而不是先按商业产品设想。
- **Agent runtime 学习**：从 Pi 等公开系统出发，研究事件、会话、工具、耐久执行、轨迹比较与评测。

## 当前方向

我希望长期积累可靠的数据与 Agent 基础设施：能够记录证据、暴露失败边界，并支持可复现实证研究的软件。

Python 是我的主要语言；目前通过公开 Agent runtime 源码学习 TypeScript。

邮箱：[wwk990630@gmail.com](mailto:wwk990630@gmail.com)
