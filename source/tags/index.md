---
title: 标签
date: 2018-01-05 00:00:00 
type: "tags"
-tags: 碎碎念
comments:  false

{% tabs Unique name, [index] %}
<!-- tab [Tab caption] [@icon] -->
Any content (support inline tags too).
<!-- endtab -->
{% endtabs %}
{% tabs test1 %}  # {% tabs test1, 3 %}，预选第三个页

<!-- tab --> #展示名字test1 1
**This is Tab 1.**
<!-- endtab -->

<!-- tab 相册@fab fa-apple-pay --> #自定义了图标和名称，展示名字相册
**This is Tab 2.**
<!-- endtab -->

<!-- tab 我的名字-->  #自定义了名称，展示名字 我的名字
**This is Tab 3.**
<!-- endtab -->

{% endtabs %}
---