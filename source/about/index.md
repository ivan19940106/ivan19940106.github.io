---
title: about
date: 2022-09-10 01:19:10
---
![me with maple leaves](/about/maple.jpeg)

### 徐暢可（Ivan Hsu）

---

> Throughout the centuries there were men who took first steps down new roads armed with nothing but their own vision. - Ayn Rand, Novelist 👨‍💻

- [x] 1994 年生於台灣台北市。
- [x] 台科弦韻吉他社 102 級文書。
- [x] 2016 年冬季學期於德國阿沙芬堡應用科技大學交換。
- [x] 2017 年派駐中國深圳工作、2019 年回台灣工作生活。
- [x] 2020 年轉職成為網頁工程師。
- [ ] [Check out my handmade portfolio, NOW!](https://ivan19940106.github.io/Kyoto-little-trip/portfolio/twitter-like%20rezume/index.html)

```
<?php

namespace Life

use Humankind;
use IvanHsu;

class Me extends Humankind
{
    private $ivanhsu;

    public function __construct(
        IvanHsu $ivanhsu
    ) {
        $this->ivanhsu = $ivanhsu;
    }

    $myAttemptions = ['guitar', 'japanese', 'writing', 'programming'];

    $myTrueCalling = array_intersect($this->ivanhsu->interests, $myAttemptions);

    echo $myTrueCalling; // programming
}
```
