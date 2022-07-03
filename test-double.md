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

[comment]: # (1. 왜 '테스트 더블을 주제로 선정했는 지')

Jimmy | Shopl & Company | June 3, 2022

# 테스트 더블

[comment]: # (!!!)
[comment]: # (1. 유래를 통한 테스트 더블의 이해)
[comment]: # (2. 테스트에서 테스트 더블이 어떤 역할을 어떻게 대신하는 지 )
[comment]: # (## 주석 - XUnit Test Patterns )

스턴트 더블 사진

<br />
<br />
<br />
<div style="text-align:right;font-size:20px;">
XUnit Test Patterns, 2002
</div>

[comment]: # (!!!)

### 간단한 문제 예제
```java
public void createOrder (){
    System.out.println("hello")
}
```

[comment]: # (!!!)

테스트 더블 정의

[comment]: # (!!!)

## Dummy
## Stub
## Fake
## Spy
## Mock

[comment]: # (!!!)

# Dummy
<br />
<br />


