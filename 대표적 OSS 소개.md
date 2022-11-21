# 대표적 OSS 소개

## 1. 리눅스 (Linux)

### 📖 리눅스란?

1991년 9월 17일 **리누스 토르발스** 가 처음 출시한 운영 체제 커널인 리눅스 커널에 기반을 둔 오픈 소스 유닉스 계열 운영 체제 계열이다. 
리눅스는 **유닉스(Unix)** 라는 운영체제를 기반으로 하고 있으며, 뛰어난 안정성과 보안성, 높은 신뢰성과 성능이 특징이다.  
  현재 다양한 사용자가 사용 할 수 있는 멀티 유저(multi-user)와 멀티 태스킹(multi-tasking)을 지원하고 있다.
 
###### Multi-User: 여러사용자가 동시에 하나의 시스템에 접근할 수 있음
###### Multi-Tasking: 여러 개의 task(작업)를 동시에 실행하고, 교대로 컴퓨터의 자원을 사용할 수 있는 기능

### ⚙ 리눅스의 구조
  
![image](https://user-images.githubusercontent.com/114379800/203022410-6e5390e6-e69f-400d-96d5-4bf1070cc0ab.png)

**응용프로그램** 에서 사용자가 명령을 내리면 **shell(셸, 쉘)** 은 이 명령을 **해석** 합니다. 해석된 사용자 입력 명령어를 kernel(커널)에게 전달합니다.  
**kernel** 은 하드웨어를 제어하는 코드를 통해 **소프트웨어와 커뮤니케이션** 을 하며, 시스템의 모든 자원을 **통제/관리** 하는 역할을 수행합니다.

###### * 커널:  커널(kernel)은 컴퓨터 운영 체제의 핵심이 되는 컴퓨터 프로그램 보안/ 자원관리/ 추상화 등의 역할을 한다.
###### * shell을 명령어 해석기라고도 부른다.

### 🏢 리눅스 활용
다양한 분야에서 리눅스를 사용하고 있으며,  
리눅스를 활용하는 회사는 구글, 삼성전자, 인텔등이 있다.


## 2. 비쥬얼 스튜디오 코드 (Visual Studio Code)

### 📖 VSCODE란?

**비주얼 스튜디오 코드(영어: Visual Studio Code)**  또는 코드는 마이크로소프트가 마이크로소프트 윈도우, macOS, 리눅스용으로 개발한 소스 코드 편집기이다.  깃허브의 일렉트론(Electron) 을 기반으로 만들어져 맥OSmacOS, 리눅스Linux, 윈도우Windows 등 메이저 운영체제를 모두 지원하고 있다.

###### * 일렉트론 : 청자오(Cheng Zhao)가 개발한 오픈 소스 프레임워크의 하나

### ✨ 기능

비주얼 스튜디오 코드는 소스 코드 편집기로, 다양한 프로그래밍 언어를 지원하며 각 언어와 함께 사용할 수 있는 편리한 기능들을 제공한다  
작성 중인 문서의 코드 페이지를 바꾸거나 줄바꿈 문자(LF 또는 CRLF)를 선택할 수 있고, 편집중인 소스 코드가 어떤 프로그래밍 언어를 사용하는지 설정할 수 있다.
플러그인을 통해 편집 기능 추가 및 프로그래밍 언어 지원 등 새로운 확장 기능을 추가할 수 있다.


## 3. 리액트 (React)

### 🐱‍🚀 리액트란?

React는 웹 프레임워크로, 자바스크립트 라이브러리의 하나로서 사용자 인터페이스를 만들기 위해 사용되며 웹/앱의 View를 개발할 수 있도록 하는 인기있는 라이브러리이다.

### 특징


**1.Data Flow**

React는 데이터의 흐름이 한 방향으로만 흐르는 단방향 데이터 흐름을 가진다.

**2. Component 기반 구조**

Component는 독립적인 단위의 소프트웨어 모듈을 말한다.
즉, 소프트웨어를 독립적인 하나의 부품으로 만드는 방법이다.

**3. Virtual Dom**

먼저, DOM은 Document Object Model의 약자이다.
DOM은 html, xml, CSS 등을 트리 구조로 인식하고, 데이터를 객체로 간주하고 관리하며
DOM Tree 구조와 같은 구조체를 Virtual DOM으로 가지고 있습니다.

**4. Props and State**

Props란 부모 컴포넌트에서 자식 컴포넌트로 전달해 주는 데이터이며
State는 컴포넌트 내부에서 선언하며 내부에서 값을 변경할 수 있다.


## 4. 텐서플로 (tensorflow)

### 📝 텐서플로란?

**텐서플로(TensorFlow)** 또는 텐서플로우는 다양한 작업에대해 데이터 흐름 프로그래밍을 위한 오픈소스 소프트웨어 라이브러리이다. 기본적으로 C++로 구현 되어 있으며, 아래의 그림과 같이 Python, Java, Go 등 다양한 언어를 지원한다. 하지만, 파이썬을 최우선으로 지원 브라우저에서 실행가능한 시각화 도구인 텐서보드(TensorBoard)를 제공하여, 딥러닝 학습 과정을 추적하는데 유용하게 사용된다.

![image](https://user-images.githubusercontent.com/114379800/203028264-b973ebe1-a96a-4e9d-b99a-1a1ab4bb7312.png)

딥러닝에서 데이터를 의미하는 **Tensor** 와 데이터 플로 그래프를 따라 연산이 수행되는 형태를 합처 **TensorFlow** 라고 하는 것이다. 



## 5. 파이토치 (pythorch)

### 🔥 파이토치란?

파이토치란 2016년에 발표된 딥러닝을 구현을 위한 파이썬 기반의 오픈소스 머신러닝 라이브러리이다.  facebook  인공지능 연구팀에 의해 개발되었으며, Define by Run의 딥러닝 구현 패러다임이 특징이다. 텐서플로 보다 쉽게 간결하고 빠른 구현가능

![image](https://user-images.githubusercontent.com/114379800/203030250-5b292d18-cc23-4fae-99d3-ff42269a3725.png)


###### *Define and Run는코드를 직접 돌리는 환경인 세션을 만들고, placeholder를 선언하고 이것으로 계산 그래프를 만들고(Define), 코드를 실행하는 시점에 데이터를 넣어 실행하는(Run) 방식


## ✔ 참고문헌

* <https://velog.io/@soryeongk/LinuxBasic>
* <https://www.44bits.io/ko/keyword/visual-studio-code>
* <https://ko.wikipedia.org/wiki/%EB%B9%84%EC%A3%BC%EC%96%BC_%EC%8A%A4%ED%8A%9C%EB%94%94%EC%98%A4_%EC%BD%94%EB%93%9C>
* <https://velog.io/@jini_eun/React-React.js%EB%9E%80-%EA%B0%84%EB%8B%A8-%EC%A0%95%EB%A6%AC>
* <https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=os2dr&logNo=221565409684>
