# All about Github Readme<br>(Markdown Syntax, Readme Templates)<br>깃허브 리드미를 위한 마크다운 문법과 리드미 템플릿

> Tips, guides, cheatsheets and templates for Github README.md  
> 깃허브 리드미를 위한 팁, 가이드, 치트시트 그리고 템플릿

### Table of Contents | 목차

1. [Markdown syntax for GMF | 깃허브맛 마크다운](#github)
    - [Markdown | 마크다운이란?](#markdown--마크다운이란)
    - [Basic Syntax Cheatsheet | 기본 문법](#basic-syntax-cheatsheet--기본-문법)
2. [Advanced Usages of Markdown | 마크다운 활용법](#advanced-usages-of-markdown--마크다운-활용법)
    - [Table of Contents (TOC) | 목차](#table-of-contents-toc--목차)
    - [Toggle | 토글](#toggle--토글)
    - [Footnotes | 주석](#footnotes--주석)
    - [Badges | 뱃지](#badge--뱃지)
3. [Readme Templates | 리드미 템플릿]()
    - [Personal side projects | 개인 프로젝트]()
    - [Github guide for Open Source Projects | 오픈소스 프로젝트]()
5. [References | 참고자료]()
<br />

## Markdown syntax for GFM | 깃허브맛 마크다운 {#github}

> Markdown is a lightweight markup language for plain-text formatting

### Markdown | 마크다운이란?
- markdown은 웹에 텍스트 문서를 작성할 수 있도록 만들어진 규칙이다.  
- 웹 문서를 작성하는 markup 언어를 경량화하여, 읽기 쉽고(easy-to-read), 쓰기 쉬운(easy-to-write) 직관적인 문법을 사용한다.
- `.md` 확장자 파일로 vscode를 비롯한 다양한 텍스트 에디터에서 작성할 수 있다.
- markdown은 HTML로 변환되어 웹 상에 표기되기 때문에, markdown에서 지원하지 않는 기능은 HTML 태그를 사용할 수 있다.
- 플랫폼과 에디터마다 주요한 문법은 공통으로 지원하지만, 세부적인 규칙은 결과물이 달라질 수 있다.
- github는 GMF(Github Flavored Makrdown, 깃허브 맛😋 마크다운)을 사용한다.
  - `README.md`와 같은 `.md` 확장자 파일
  - Issues 와 Pull requests
  - Gists

### Basic Syntax Cheatsheet | 기본 문법
<details>
  <summary><b>Headers | 제목</b></summary>
  
  ####   
  ```
    # <h1> -> underline 있음
    ## <h2> -> underline 있음
    ### <h3>
    #### <h4>
    ##### <h5>
    ###### <h6>
  ```
  ####   
</details>

<details>
  <summary><b>Emphasis | 강조</b></summary>
  
  ####   
  ```
    *italic* or _italic_
    **bold** or __bold__
    ~~strikethrough~~
    <u>underline</u>
  ```
  ####   
</details>
<details>
  <summary><b>Line Breaks | 줄바꿈</b></summary>
  
  ####   
  - 2 or more spaces | 2번 이상 띄어쓰기
  - `<br />`
  ####   
</details>

<details>
  <summary><b>Lists | 리스트</b></summary>
  
  ####   
  **Unordered**
  ```
    - item 1 -> -, +, * 사용 가능
    - item 2
      - item 2a
      - item 2b
  ```
  **Ordered**
  ```
    1. item 1
    1. item 2
      1. item 2a
      1. item 2b
  ```
  **Task lists**
  ```
    - [ ] todo
    - [X] completed
  ```
  ####   
</details>

<details>
  <summary><b>Images | 이미지</b></summary>
  
  ####   
  ```
  ![alt text](url)
  
  ![GitHub Logo](/images/logo.png)
  ```
  ####   
</details>
<details>
  <summary><b>Links | 링크</b></summary>
  
  ####   
  ```
  [text](url)
  
  [GitHub](http://github.com)
  ```
  ####   
</details>

<details>
  <summary><b>Blockquotes | 인용</b></summary>
  
  ####   
  ```
  > Blockquotes
  ```
  ####   
</details>
<details>
  <summary><b>Codes | 코드</b></summary>
  
  ####   
  **Inline | 인라인**
  ```
  `inline code` -> backticks
  ```
  **Code Blocks | 코드블럭**
  <pre>```javascript
console.log('hello world')
```</pre>
  ####   
</details>

</details>

<details>
  <summary><b>Tables | 표</b></summary>
  
  ####   
  ```
  | head | head | head |
  | --- | :---: | ---: | -> 정렬 | left | center | right |
  | body | body | body |
  ```
  ####   
</details>

<br />

## Advanced Usages of Markdown | 마크다운 활용법

### Table of contents (TOC) | 목차

```
[Heading ID](#heading-id)

## Heading ID {#custom-id}
```

```
### Table of Contents
1. [Title A](#title-a)
    - [Subtitle 1](#subtitle-1)
2. [Title B - 제목 B](#title-b--제목-b)
    - [Subtitle 2 - 부제목 2]()
    
## Section Title
### Subtitle 1
## Section Title - 제목
```


- header-link 
### Toggles | 토글

### Footnotes | 주석

### Badge | 뱃지

## Readme Templates

### Personal side projects
### Github guides
