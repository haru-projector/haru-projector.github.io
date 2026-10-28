# haru-projector.github.io

Haru Projector（开源的电视 / 投影仪桌面）的网站：

- `/` 首页，`/privacy.html` 隐私政策（Google 登录的同意屏幕和审核要用）
- `/oauth/` Google 登录的中转页：电视上扫码 → 手机登录 Google → Google 只能跳回公网 HTTPS 地址，于是跳到这里 →
  这个页面在手机浏览器里马上把授权码交给家里局域网里的电视（地址在 `state` 里）。纯静态，不存任何东西；只接受局域网地址。
