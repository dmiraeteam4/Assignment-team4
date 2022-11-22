# OSS 저작권

일반적으로 오픈소스 소프트웨어는 소스 코드가 공개돼 있고, 누구나 내려받아 사용할 수 있지만 저작권 자체가 없는 것은 아니며 라이선스 또한 존재한다. 
저작권자가 허락한 ***범위*** 내에서 자유롭게 사용할 권리와 함께 지켜야 할 ***의무사항*** 이 있는데 이를 `오픈소스 라이선스` 라고 한다.

만약 사용자가 해당 소프트웨어의 오픈소스 라이선스를 준수하지 않으면 저작권자가 허락한 범위가 아니기 때문에 저작권 위반이 된다.  
즉, 오픈소스 소프트웨어에도 일반적 상용 소프트웨어와 마찬가지로 기본적으로 저작권법 체계가 적용되고, 저작권자가 허락한 범위를 넘어 사용하면 법적 분쟁에 휘말릴 수 있다.

## 📃 오픈소스 라이선스

### 1. 주요 의무사항

> **저작권, 개발자 및 기여자 정보**

```
<Apache License 2.0>
4. c. You must retain, in the Source form of any Derivative Works that You distribute,
all copyright, patent, trademark, and attribution notices from the Source form of the
Work, excluding those notices that do not pertain to any part of the Derivative Works;
```  
  
  
> **코드를 수정한 경우 수정한 정보의 표시**  

수정한 사람, 수정 일자 등 수정에 관한 내용을 포함하도록 함 (원본과 구별)
```
<Apache License 2.0>
2. You must cause any modified files to carry prominent notices stating that You changed the files.
```

> **라이선스 정보의 제공**

이용자들이 오픈소스에 관한 권리를 잘 이해할 수 있도록 배포자가 라이선스의 사본 첨부
```
<Apache License 2.0>
1. You must give any other recipients of the Work or Derivative Works a copy of this License.
```

> **동일한 라이선스로 재배포할 것** ***(copyleft)***  

라이선스에 따라 큰 차이를 보임. ***GPL***(FSF가 말하는 "소프트웨어의 자유"를 지키기 위한 구체적인 수단)을 대표로 하는 카피레프트 라이선스들은 이용자들이 소프트웨어를 수정한 후 배포하고자 할 때 
수정된 소프트웨어에도 동일한 라이선스로 배포할 것을 요구함

```
<GPL 2.0>
 
2. You may modify your copy or copies of the Program or any portion of it, thus forming
a work based on the Program, and copy and distribute such modifications or work under
the terms of Section 1 above, provided that you also meet all of these conditions:
 b) You must cause any work that you distribute or publish, that in whole or in part
contains or is derived from the Program or any part thereof, to be licensed as a whole
at no charge to all third parties under the terms of this License.
```

> **소스코드의 제공**  

카피레프트 조항을 포함하는 라이선스의 경우, 소스코드 함께 배포

```
예) GPL 2.0
 
3. You may copy and distribute the Program (or a work based on it, under Section 2) in
object code or executable form under the terms of Sections 1 and 2 above provided that
you also do one of the following:
 a) Accompany it with the complete corresponding machine-readable source code,
 ```
 
### 2. 확인 방법

> **1) 소스 코드 파일 상단 주석 확인**  

<img src="https://user-images.githubusercontent.com/114379800/203342242-908b1c0a-5ab6-4442-8c53-6626db19d0d7.png" height="250"/>

> **2) root 폴더 내 LICENSE (혹은 COPYING) 파일 확인**

> **3) README 또는 웹사이트에서 확인**

## 💡 주요 라이선스  

## 1. Berkeley Software Distribution(BSD) License 

> + *버클리 대학* 에서 만든 라이선스로 공공기관에서 만들어낸 것이기에 공공의 몫으로 돌려주자는 의미가 강해서 라이선스 자체에는 아무런 ***제한 없이 누구나 자신의 용도로 사용*** 할 수 있도록 만들어졌다. 
> + **라이선스 및 저작권 표시** 조건 외에 굉장히 자유로운 라이선스 중 하나이다.

<img src="https://user-images.githubusercontent.com/114379800/203363937-05108906-d6bd-4516-a5b6-ac49e50e85dd.png" height="100"/>

## 2. Apache License

> + *아파치 소프트웨어 재단*  자체적으로 만든 라이선스이다. 
> + 소스코드에 대한 공개 의무 등의 의무사항은 없다.
> + 하지만 아파치 ***라이선스의 소스코드를 수정*** 하여 배포하는 경우 수정사항에 대한 고지(수정일, 수정내용 등)를 포함해야 한다.

<img src="https://user-images.githubusercontent.com/114379800/203364165-12bdc099-9185-4fa1-bd56-4ead7a171283.png" height="200"/>

## 3. GNU General Public License(GPL)

> + *자유 소프트웨어 재단(Free Software Foundation, FSF)* 에서 만든 라이선스로 GNU 프로젝트로 배포하는 소프트웨어에 적용하기 위하여 리처드 스톨먼(Richard Stallman)이 만든 라이선스이다. 
> + 가장 강한 제약 조건을 포함하고 있는 ***카피레포트 조항과 소스코드 제공 의무*** 를 가지고 있다.  

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/GPLv3_Logo.svg/220px-GPLv3_Logo.svg.png)

## 4. GNU Lesser GPL(LGPL)

> + 주로 라이브러리에 사용하기 위해 *FSF* 가 GPL과는 별도로 만든 라이선스이다. 
> + 단순히 소프트웨어를 사용하기만 하더라도 해당 소스코드를 GPL로 공개해야 하는 부담감이 있는데 그것을 줄여주기 위해서 ***라이브러리 자체를 수정***한 경우에는 ***카피레포트 조항***을 적용
> + ***응용프로그램***은 ***카피레포트 조항 적용 x, 소스코드 제공 의무도 없다.***  

![image](https://user-images.githubusercontent.com/114379800/203363715-c0d31fee-d294-42a6-9b00-5b4f41bfb7dd.png)

## 5. Mozilla Public License(MPL)

> + *넷스케이프사*가 자사의 브라우저를 오픈소스로 배포하면서 만든 라이선스이다. 
> + 소스코드와 실행파일의 저작권을 분리함으로써 ***사용한 MPL 소프트웨어와 수정한 MPL 소프트웨어***에는 ***카피레포트 조항***을 적용
> + 실행파일은 독점 라이선스를 가질 수 있다.

![image](https://user-images.githubusercontent.com/114379800/203364450-62d98974-fd84-4382-9095-5ddb49eb535a.png)

## 참고문헌
+ <https://www.fnnews.com/news/201811281705502816>
+ <https://www.olis.or.kr/license/licenseGuide.do>
+ <https://sktelecom.github.io/guide/use/license/>
+ <https://naver.github.io/OpenSourceGuide/book/UsingOss/the-legal-side-of-opensource.html>
+ <https://www.oss.kr/oss_license>
+ <https://codenamu.org/2014/10/10/popular-opensource-license>

