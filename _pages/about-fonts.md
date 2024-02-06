---
title: "글꼴에 관하여"
permalink: /about-fonts/
read_time: true
toc: true
sitemap: true
---
<i class="fa-sharp fa-regular fa-file-pen"></i> *마지막 수정: 2024. 2. 6.*

# 글꼴별 소스
글꼴별 라이센스는 [크레딧](/credits) 참조 바랍니다.
{: .notice--warning}

* 웹 폰트(자체 저장소): Montserrat, Gentium Plus
* 웹 폰트(외부 CDN): Kosugi(Google Fonts), Font Awesome
* 개별 설치: 본고딕, Jigmo

*****

# 개요
본 사이트에서는 주 글꼴로 Montserrat, 본고딕(Source Han Sans)을 이용하고 있습니다(기타 아이콘 등은 [Font Awesome](https://fontawesome.com) 사용 중).

Montserrat는 웹 폰트를 이용하고 있어 웬만한 기기에서는 정상적으로 출력이 될 것입니다.

다만 본고딕은 한국어뿐만 아니라 일본어, 중국어 정체/간체까지 아우르는 글꼴이기에 웹 폰트로 올리면 로딩 시간이 길어질 것을 고려해 웹 폰트로 올리지는 않았습니다.

본고딕이 설치되지 않은 환경이라면 여러분이 사용하고 계신 운영체제의 기본 글꼴이 나올 것입니다.

본고딕을 설치하시려면 아래 링크를 참조 바랍니다(설치하실 때 언어별로 전부 설치하시는 것을 권장합니다).

[본고딕(GitHub)](https://github.com/adobe-fonts/source-han-sans), [최신 버전(2.004R) 직링크](https://github.com/adobe-fonts/source-han-sans/archive/refs/tags/2.004R.zip)

혹시 Montserrat를 직접 설치하고 싶으시면 아래 링크 참조 바랍니다.

[링크(GitHub)](https://github.com/JulietaUla/Montserrat), [최신 버전(7.222) 직링크](https://github.com/JulietaUla/Montserrat/archive/refs/tags/v7.222.zip)

# 한자 글꼴
본 사이트에서는 각 나라에 맞는 한자 글꼴을 알맞게 출력하기 위해 위의 본고딕을 활용하고 있습니다. 본고딕을 설치하시지 않더라도 대부분의 환경에서는 정확한 글꼴로 출력될 것으로 예상하지만, 간혹 정상적으로 출력되지 않는 환경이 일부 있을 수 있습니다. 이 점까지는 제 사정상 모든 환경을 다루지는 못하기에 완벽하게 해결이 불가하다는 점 양해 부탁드리겠습니다.

## 각국 자형의 차이
유니코드에서는 한자를 배당할 때 미묘한 자형 차이는 통합했기에 해당 국가의 언어를 적을 때에는 반드시 해당 언어의 글꼴을 사용해야 합니다.

왼쪽부터 한국식, 일본식, 중국어 정체, 중국어 간체입니다.

U+793E(모일 사): <span lang="ko" style="font-size: x-large;">社</span> <span lang="ja" style="font-size: x-large;">社</span> <span lang="zh-tw" style="font-size: x-large;">社</span> <span lang="zh-cn" style="font-size: x-large;">社</span>

U+9053(길 도): <span lang="ko" style="font-size: x-large;">道</span> <span lang="ja" style="font-size: x-large;">道</span> <span lang="zh-tw" style="font-size: x-large;">道</span> <span lang="zh-cn" style="font-size: x-large;">道</span>

U+6D88(사라질 소): <span lang="ko" style="font-size: x-large;">消</span> <span lang="ja" style="font-size: x-large;">消</span> <span lang="zh-tw" style="font-size: x-large;">消</span> <span lang="zh-cn" style="font-size: x-large;">消</span>

U+60C5(뜻 정): <span lang="ko" style="font-size: x-large;">情</span> <span lang="ja" style="font-size: x-large;">情</span> <span lang="zh-tw" style="font-size: x-large;">情</span> <span lang="zh-cn" style="font-size: x-large;">情</span>

위 예시는 일부에 불과합니다. 이것 말고도 유니코드에는 이런 차이가 제법 많습니다.

~~사실 이런 미묘한 차이도 그냥 다른 코드로 배당해 놓았으면 편리했을텐데 유니코드 컨소시엄은 그걸 너무 늦게 깨달았나 봅니다...~~

## 확장 신자체 글꼴
일본어의 일부 확장 신자체를 지원하기 위해 본 사이트에서는 Kosugi라는 글꼴을 사용하고 있습니다. Kosugi 역시 웹 폰트로 가져오기에 웬만한 기기에서는 정상적으로 출력이 될 것입니다.

직접 설치하시려면 [링크(클릭)](https://fonts.google.com/specimen/Kosugi) 참조 바랍니다(Download Family 클릭).

이 사이트에서 사용되는 것을 보시려면 브라우저의 개발자 도구를 여신 후 태그 속성에 `class="kasai"`로 적용하시면 됩니다.

예시: <span class="kasai" style="font-size: x-large;">迂</span>(에돌 우)

## 확장 한자
이 문단은 [백괴사전의 유니코드 특수 문자 도움말](https://uncyclopedia.kr/wiki/%EB%8F%84%EC%9B%80%EB%A7%90:%EC%9C%A4%ED%9D%AC%EC%BD%94%EB%93%9C_%ED%8A%B9%EC%88%98_%EB%AC%B8%EC%9E%90)를 참조했습니다. 사실 여기 가보시면 한자뿐만 아니라 여러 문자의 글꼴 관련 설명도 많이 있어 꽤 유용합니다.<br><img src="/assets/images/by-nc-sa.svg" alt="CC BY-NC-SA 3.0" title="CC BY-NC-SA 3.0">
{: .notice--info}

유니코드에는 한자가 매우 많습니다. 진짜 많이요.

그렇다 보니 기본 한자 영역에 추가되지 못하고 확장 영역에 추가된 한자들이 엄청 많습니다. ~~심지어 지금 확장 I까지 있읍니다~~

이런 확장 한자들을 일반적인 글꼴들로는 일부만 표시되거나 아예 표시를 하지 못하기 때문에 전용 글꼴이 필요합니다.

대표적으로는 하나조노 명조가 있었으나 이 글꼴은 유니코드 10.0까지의 한자밖에 표시를 못한다는 단점이 있고, 오랫동안 업데이트가 없었습니다(마지막 업데이트가 2017년 9월이었나 그럴걸요?).

그래서 하나조노의 대체품으로 최신 유니코드 15.1의 한자까지 지원하는 [Jigmo](https://kamichikoichi.github.io/jigmo/)라는 글꼴이 나왔습니다(최근 업데이트: 2023. 8. 16.).

Jigmo 역시 용량이 매우 큰 편이기에 웹 폰트로 올리지는 않았습니다.

혹시 개발자 도구로 보고 싶으시면 태그 속성에 `class="exk"`로 적용하시면 됩니다.

### 이 외의 글꼴로는...

* **[cutra_AppendingToHanaMin](https://ko.glyphwiki.org/wiki/Group:cutra_AppendingToHanaMin)**

하나조노의 확장판 격인 글꼴입니다(확장 C~H, URO+, 확장 A+, 확장 B+, 확장 C+ 영역 지원).

* **[Plangothic](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic)**

하나조노의 고딕체판 글꼴 정도로 보시면 됩니다(~유니코드 15.0).

### 확인
기본 한자 영역은 전부 보이실 것으로 판단하고 여기에 넣진 않겠습니다.

나중에 각 영역의 모든 한자를 정리한 글을 작성할 예정입니다.

* **확장 A**

<p class="exk" style="font-size: xx-large;">㐀 㔀 㘀 㜀 㠀 㤀 㨀 㬀</p>

* **확장 A+**

<p class="exk" style="font-size: xx-large;">䶶 䶷 䶸 䶹 䶺 䶻 䶼 䶽 䶾 䶿</p>

* **확장 B**

<p class="exk" style="font-size: xx-large;">𠀀 𡀀 𢀀 𣀀 𤀀 𥀀 𦀀 𧀀</p>

* **확장 B+**

<p class="exk" style="font-size: xx-large;">𪛗 𪛘 𪛙 𪛚 𪛛 𪛜 𪛝 𪛞 𪛟</p>

* **확장 C**

<p class="exk" style="font-size: xx-large;">𪜀 𪠀 𪤀 𪨀 𪬀 𪰀 𪴀 𪸀</p>

* **확장 C+**

<p class="exk" style="font-size: xx-large;">𫜵 𫜶 𫜷 𫜸 𫜹</p>

* **확장 D**

<p class="exk" style="font-size: xx-large;">𫝀 𫝐 𫝠 𫝰 𫞀 𫞐 𫞠 𫞰</p>

* **확장 E**

<p class="exk" style="font-size: xx-large;">𫠠 𫠡 𫠢 𫠣 𫠤 𫠥 𫠦 𫠧</p>

* **확장 F**

<p class="exk" style="font-size: xx-large;">𬺰 𬺱 𬺲 𬺳 𬺴 𬺵 𬺶 𬺷</p>

* **확장 G**

<p class="exk" style="font-size: xx-large;">𰀀 𰀁 𰀂 𰀃 𰀄 𰀅 𰀆 𰀇</p>

* **확장 H**

<p class="exk" style="font-size: xx-large;">𱍐 𱍑 𱍓 𱍕 𱍗 𱍟 𱏐 𱟛</p>

* **확장 I**

<p class="exk" style="font-size: xx-large;">𮯰 𮰔 𮱏 𮱶 𮲐 𮲪 𮵏 𮷍</p>

* **URO+**

<p class="exk" style="font-size: xx-large;">龦 龧 龨 龩 龪 龫 龬 龭 龮 龯</p>
<p class="exk" style="font-size: xx-large;">龰 龱 龲 龳 龴 龵 龶 龷 龸 龹</p>
<p class="exk" style="font-size: xx-large;">龺 龻 龼 龽 龾 龿 鿀 鿁 鿂 鿃</p>
<p class="exk" style="font-size: xx-large;">鿄 鿅 鿆 鿇 鿈 鿉 鿊 鿋 鿌 鿍</p>
<p class="exk" style="font-size: xx-large;">鿎 鿏 鿐 鿑 鿒 鿓 鿔 鿕 鿖 鿗</p>
<p class="exk" style="font-size: xx-large;">鿘 鿙 鿚 鿛 鿜 鿝 鿞 鿟 鿠 鿡</p>
<p class="exk" style="font-size: xx-large;">鿢 鿣 鿤 鿥 鿦 鿧 鿨 鿩 鿪 鿫</p>
<p class="exk" style="font-size: xx-large;">鿬 鿭 鿮 鿯 鿰 鿱 鿲 鿳 鿴 鿵</p>
<p class="exk" style="font-size: xx-large;">鿶 鿷 鿸 鿹 鿺 鿻 鿼 鿽 鿾 鿿</p>

# 확장 가나(헨타이가나 등) 글꼴
헨타이가나도 Jigmo에서 모두 지원하는 것으로 보입니다.

예시: <span class="exk" style="font-size: xx-large;">𛀂𛀆𛀁𛀙𛄟 𛀀𛄠𛄡𛄢 𛅐𛅑𛅒𛅤𛅥𛅦𛅧</span>

# IPA 글꼴
이 사이트에서는 IPA를 표기하기 위해서 Gentium Plus를 사용합니다. 이 글꼴도 웹 폰트를 이용하였으므로 대부분의 환경에서는 정상적으로 나올 것입니다.

직접 설치하고 싶으신 분은 [이 링크(클릭)](https://software.sil.org/gentium/download/)에서 다운로드하실 수 있습니다.

개발자 도구로 보고 싶으시면 태그 속성에 `class="ipa"`로 적용하시면 됩니다.

예시: <span class="ipa" style="font-size: x-large;">[𝼅𝼆𝼀ꞯ]</span>