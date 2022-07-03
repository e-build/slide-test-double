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

<div style="text-align:center;">
    <img src="resources/stunt-double.jpeg" width="400px" height="450px" style="border-radius:8px;">
</div>

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

<br/>

<p style="font-size:30px;">
    <span style="color:#ba2552; text-decoration:underline;"><strong>테스트 목적</strong></span>을 위해 프로덕션 
    <span style="color:#ba2552; text-decoration:underline;"><strong>객체를 다른 무언가로 교체</strong></span>하는 <br/>
    모든 경우를 표현하는 용어
</p>

<div style="display:flex; justify-content:center;">
    <div style="border-left:3px solid #a2a9b3; font-size:25px; font-style:italic; color:#a2a9b3;        box-sizing:content-box; width:fix-content; padding-left:20px;">
    Test Double is a generic term for any case where you replace <br/>
    a production object for testing purposes.
    </div>
</div>

<br/>

<div style="text-align:right; font-size:17px;">
    XUnit Test Patterns, 2002
</div>

[comment]: # (!!! data-auto-animate)

## Dummy
## Stub
## Fake
## Spy
## Mock

[comment]: # (!!!)

# Dummy

[comment]: # (|||)

실제로 사용되지 않지만 전달되기 위해 만들어지는 객체

* 인스턴스화된 객체만 필요하고, 기능까지는 필요하지 않은 경우
* 주로 매개변수 목록을 채우는 용도

[comment]: # (|||)

Dummy 예제

[comment]: # (!!! data-background-color="black")

# Stub

[comment]: # (|||)

Dummy가 마치 실제로 동작하는 것처럼 보이게 만든 객체.
* 미리 반환할 데이터가 정의되어 있으며, 메소드를 호출하였을 경우 그것을 그대로 반환하는 역할만 수행

[comment]: # (|||)

Stub 예제

[comment]: # (!!! data-background-color="black")

# Fake

[comment]: # (|||)

실제 동작하는 구현을 가지고 있지만, 프로덕션에서는 사용되기 적합하지 않은 객체

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






