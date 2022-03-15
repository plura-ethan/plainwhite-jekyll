---
layout: post
title:  "PLURA V5 웹방화벽(PLURA V5 WAF) 무엇이 다를까요?"
date:   2022-03-15 01:03:36 +0900
categories: Javascript NodeJS
---
종래의 웹방화벽 솔루션은 OWASP TOP 10 공격 위주의 탐지와 차단을 제공하므로, 고객별, 서비스별 취약점 대응에는 효과적이지 않습니다.또한, 통계적인 특징과 상호 데이터 분석 등을 반영해야 하는 크리덴셜 스터핑, 볼륨메트릭, SQL 인젝션 공격 등으로 인한 실시간 데이터유출의 해킹 공격 대응은 대단히 어렵습니다.반면에 프루라 웹방화벽은 모든 기능을 완전 자동화하고 PLURA V5 SIEM과 연동하여 크리덴셜 스터핑, 볼륨메트릭, 데이터유출 해킹 공격에  자동 탐지와 차단을 제공합니다. 정말 경이로운 제품입니다.

```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
