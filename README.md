# All about Github Readme, 깃허브 리드미 그만 검색하자.

Tips, guides, cheatsheets and templates for Github README.md   

깃허브 리드미를 위한 팁과 가이드와 치트시트와 템플릿

### Table of Contents
1. [Markdown syntax for GMF, 깃허브맛 마크다운을 위한 문법](#markdown-syntax-for-gfm)
  - [Markdown](#markdown)
  - [Basic Syntax Cheatsheet](#basic-syntax-cheatsheet)
  - [Advanced Usages](#advanced-usages)
    - [TOC]()
    - [Badges]()
    - [Footnotes]()
2. [Templates]()

<br />

## Markdown syntax for GFM

<br />

> Markdown is a lightweight markup language for plain-text formatting

<br />

### Markdown
- Markdown은 웹에 텍스트 문서를 작성할 수 있도록 만들어진 규칙이다.  
- 웹 문서를 작성하는 markup 언어를 경량화하여, 읽기 쉽고(easy-to-read), 쓰기 쉬운(easy-to-write) 직관적인 문법을 사용한다.
- `.md` 확장자 파일로 vscode를 비롯한 다양한 텍스트 에디터에서 작성할 수 있다.
- Markdown은 HTML로 변환되어 웹 상에 표기되기 때문에, Markdown에서 지원하지 않는 기능은 HTML 태그를 사용할 수 있다.
- 플랫폼과 에디터마다 주요한 문법은 공통으로 지원하지만, 세부적인 규칙은 결과물이 달라질 수 있다.
- Github는 GMF(Github Flavored Makrdown, 깃허브 맛😋 마크다운)을 사용한다.
  - `README.md`와 같은 `.md` 확장자 파일
  - Issues 와 Pull requests
  - Gists

<br />

### Basic Syntax Cheatsheet
<details>
  <summary><b>Headers, 제목</b></summary>
  
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
  <summary><b>Emphasis, 강조</b></summary>
  
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
  <summary><b>Line Breaks, 줄바꿈</b></summary>
  
  ####   
  - 2 or more spaces, 2번 이상 띄어쓰기
  - `<br />`
  ####   
</details>

<details>
  <summary><b>Lists, 리스트</b></summary>
  
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
  <summary><b>Images, 이미지</b></summary>
  
  ####   
  ```
  ![Alt Text](url)
  
  ![GitHub Logo](/images/logo.png)
  ```
  ####   
</details>
<details>
  <summary><b>Links, 링크</b></summary>
  
  ####   
  ```
  [Text](url)
  
  [GitHub](http://github.com)
  ```
  ####   
</details>

<details>
  <summary><b>Blockquotes, 인용</b></summary>
  
  ####   
  ```
  > Blockquotes
  ```
  ####   
</details>
<details>
  <summary><b>Codes, 코드</b></summary>
  
  ####   
  **Inline**
  ```
  `inline code` -> backticks
  ```
  **Code Blocks**
  <pre>```javascript
console.log('hello world')
```</pre>
  ####   
</details>

</details>

<details>
  <summary><b>Tables, 표</b></summary>
  
  ####   
  ```
  | head | head | head |
  | --- | :---: | ---: | -> 정렬 | left | center | right |
  | body | body | body |
  ```
  ####   
</details>

<br />

### Advanced Usages
- TOC (table of contents)
- badge
- footnotes

## Templates
- Personal side projects
- Github guides
