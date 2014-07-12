---
layout: post
comments: yes
title: Gõ tiếng Việt trong sublime trên linux
description: Sublime&#58; "BoGo, you complete me &#58;3". Gõ tiếng Việt trong sublime trên linux chưa bao giờ thuận tiện và dễ dàng hơn...
---

Sublime: "BoGo, you complete me :3"

Gõ tiếng Việt trong sublime từng gặp khó khăn trên linux vì nó không hỗ trợ bộ gõ ibus, 1 số chiêu giang hồ từng sử dụng để gõ được tiếng Việt, như:

- Plugin [InputHelper](https://github.com/xgenvn/InputHelper): plugin này sẽ bật 1 popup nhỏ chứa 1 textbox cũng nho nhỏ để người dùng gõ tiếng Việt vào, sau đó mới insert vào sublime, khá là bất tiện.

- Plugin [VN_IME](https://github.com/yehnkay/VN_IME): plugin này bắt sự kiện modified nội dung và thực hiện việc bỏ dấu tiếng Việt bằng thuật toán riêng, đây cũng chính là nhược điểm của plugin này vì thuật toán chưa hoàn thiện, có nhiều lỗi phát sinh.

- Plugin [Sublime-Bogo](https://github.com/pirackr/Sublime-Bogo): Trên list issue của [VN_IME](https://github.com/yehnkay/VN_IME) có 1 bạn đề nghị dùng bogo-python để xử lý việc bỏ dấu tiếng Việt nhưng tác giả chưa thực hiện. Lúc này trong đầu mình đang nhen nhóm ý tưởng viết 1 plugin riêng cho sublime dùng engine bogo-python :sure:, nhưng trước khi start mình google 1 lượt để tránh trùng ý tưởng với người khác, và không biết nên vui mừng hay cụt hứng khi mình tìm ra plugin [Sublime-Bogo](https://github.com/pirackr/Sublime-Bogo), theo commit log thì plugin này chỉ mới được phát triển cách đây 1 tháng :3. Hý hửng cài thử và kết quả... thật toẹt vời, post này được mình viết trên sublime sử dụng [Sublime-Bogo](https://github.com/pirackr/Sublime-Bogo) để gõ tiếng Việt nhá nhá :3. Gõ tiếng Việt trong sublime trên linux chưa bao giờ thuận tiện và dễ dàng hơn :sexy: