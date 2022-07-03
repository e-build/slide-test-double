[comment]: # (This presentation was made with markdown-slides)
[comment]: # (This is a CommonMark compliant comment. It will not be included in the presentation.)
[comment]: # (Compile this presentation with the command below)
[comment]: # (mdslides presentation.md --include media)

[comment]: # (Set the theme:)
[comment]: # (THEME = white)
[comment]: # (CODE_THEME = base16/zenburn)
[comment]: # (The list of themes is at https://revealjs.com/themes/)
[comment]: # (The list of code themes is at https://highlightjs.org/)

[comment]: # "You can also use quotes instead of parenthesis"
[comment]: # "THEME = white"

[comment]: # (Pass optional settings to reveal.js:)
[comment]: # (controls: true)
[comment]: # (keyboard: true)
[comment]: # (markdown: { smartypants: true })
[comment]: # (hash: false)
[comment]: # (respondToHashChanges: false)
[comment]: # (Other settings are documented at https://revealjs.com/config/)

Jimmy | Shopl & Company | June 3, 2022

# 테스트 더블

[comment]: # (1. 왜 '테스트 더블을 주제로 선정했는 지')
[comment]: # (!!!)

스턴트 더블 사진
<br />
<br />
<br />
<div style="text-align:right;font-size:20px;">
XUnit Test Patterns, 2002
</div>

[comment]: # (!!!)
[comment]: # (1. 유래를 통한 테스트 더블의 이해)
[comment]: # (2. 테스트에서 테스트 더블이 어떤 역할을 어떻게 대신하는 지 )
[comment]: # (## 주석 - XUnit Test Patterns )

### 간단한 문제 예제
```java
public void createOrder (){
    System.out.println("hello")
}
```

[comment]: # (!!! data-background-color="aquamarine")

### 테스트 더블이란?
> Test Double is a generic term for any case where you replace a production object for testing purposes. There
> are various kinds of double that Gerard lists:
테스트 더블은 테스트 목적을 위해 프로덕션 객체를 다른 무언가로 교체하는 모든 경우를 표현하는 용어
<div style="text-align:right;font-size:20px;">
XUnit Test Patterns, 2002
</div>

[comment]: # (!!!)

## Dummy
## Stub
## Fake
## Spy
## Mock

[comment]: # (!!!)

# Dummy

[comment]: # (|||)

Dummy 정의

[comment]: # (|||)

Dummy 예제

[comment]: # (!!! data-background-color="black")

# Stub

[comment]: # (|||)

Stub 정의

[comment]: # (|||)

Sutb 예제

[comment]: # (!!! data-background-color="black")

# Fake

[comment]: # (|||)

Fake 정의

[comment]: # (|||)

Fake 예제

[comment]: # (!!! data-background-color="black")

# Spy

[comment]: # (|||)

Spy 정의

[comment]: # (|||)

Spy 예제

[comment]: # (!!! data-background-color="black")

# Mock

[comment]: # (|||)

Mock 정의

[comment]: # (|||)

Mock 예제

[comment]: # (!!! data-background-color="black")






