# joi-live-calendar

ICS calendar feed for 轴伊 Joi_Channel's weekly Bilibili livestreams, auto-updated from her weekly schedule posts.

轴伊 Joi_Channel 每周 Bilibili 直播日程的 ICS 日历订阅源，根据每周周表自动更新。

## Subscribe / 订阅

iPhone: Settings > Apps > Calendar > Calendar Accounts > Add Account > Other > Add Subscribed Calendar, then paste this URL:

https://ics.nanao.eu.org/joi.ics

This is served by GitHub Pages on a custom domain and is directly reachable in China. Backup URL (may not be reachable from some networks):

https://raw.githubusercontent.com/Aki894/joi-live-calendar/main/joi.ics

When a new weekly schedule is posted, the .ics file is updated in this repo and GitHub Pages redeploys it automatically — no need to re-subscribe.

## Source / 来源

- Streamer: 轴伊Joi_Channel (Bilibili UID 61639371)
- Weekly schedule topic: 轴轴轴周表
- This week (11.9~11.15): https://www.bilibili.com/opus/1268567995927494657

Events are 2 hours long (assumption) with a reminder 3 minutes before the stream starts. All times are Asia/Taipei.

## Maintenance / 维护

Weekly updates are pushed automatically with a dedicated SSH deploy key that only has access to this repository.
