**![FocusWriter 로고](https://gottcode.org/focuswriter/icon48.png)FocusWriter 사용 설명서**
============================
[FocusWriter Github URL](https://github.com/gottcode/focuswriter.git)  


**1. 프로그램 선정 이유** 
------------------
* 오픈 소스 관련 소프트웨어를 찾던 중 매력적인 소프트 웨어라고 생각 함.
* Github에 프로그램 소스가 올라와 있어 소스에 접근하기 용이함. 
* 프로그램 언어가 C++로 되어있어 이해 하기 쉬움.
* 소프트웨어 사용 설명 관련 자료가 많이 올라와 있지 않음. 
* 소프트웨어가 간단하고 많은 기능이 포함 되어 있지 않아 난이도가 어렵지 않다. 

-----------------------------

## **2. 프로그램 소개**

포커스라이터는 [Gott Code]( http://gottcode.org) 에서 만든 간단하고 편리하며 스타일리쉬한 문서 작성기 입니다.

![FocusWriter inro image](http://cfile220.uf.daum.net/image/2352EA405231F5C028763F)  


한글이나 워드 같은 문서 작성 편집 도구가 아닌 오로지 문서 작업에 집중 할 수 있도록 도와주는 프로그램 이므로 그림, 사진의 삽입 기능이 없고, 심지어 글꼴, 색상, 크기 변경 기능을 지원 하지 않으며, 텍스트 에디터의 신텍스 하이라이팅 같은 코딩에 도움이 되는 기능을 제공 하는것도 아닙니다. 

포커스 라이터는 오로지 글쓰기만을 위해 만들어진 프로그램입니다. 컴퓨터에서 글을 쓰려고 할 때 바탕화면에 있는 아이콘들, 시계등 글쓰기를 방해하는 요소가 상당히 많습니다.  포커스 라이터는 이러한 방해 요소들을 제거 능률적인 작업 환경을 만들 수 있게 도와주며 글쓰기의 재미도 느끼게 해 줄 수 있습니다. 

지원되는 파일 형식은 TXT,basic RTF,basic ODT  입니다.

>TXT = plain text  
basic RTF = Rich Text File  
basic ODT = OpenDocument Text 


### 설치법


* **Windows**

    [FocusWriter 사이트](https://gottcode.org/focuswriter/)에서 운영체제 Windows를 선택한 후 Download 버튼을 누른다.


* **Linux**
 
 1. 터미널을 열어서 (Ctrl+Alt+T) PPA:를 추가한다.

	   `sudo add-apt-repository ppa:gottcode/gcppa`
	   
   

	![ppa추가](http://ubuntuhandbook.org/wp-content/uploads/2017/12/mame-ppa-600x73.jpg)

 2.  Software Updater 를 실행한 후 FocusWriter에 체크를 한 후 Install을 한다.

		![Software Updater](http://ubuntuhandbook.org/wp-content/uploads/2016/08/upgrade-focuswriter.jpg)

		또는 명령어를 통해서 설치가 가능하다.
		
		`sudo apt update && sudo apt install focuswriter`

---------------------------------------

## 3. **기능 설명** 

### *스킨 변경 기능* 

 FocusWriter의 아주 심플한 기능중에서 이용자들이 FocusWriter를 선택하게 만든 첫번째 이유는 바로 테마 스킨(Skin)!!  

* **테마 변경 법**
	>설정탭에서 테마를 누르면 선택창에서 간단하게 바꿀 수 있다.
	![테마 변경 법](http://imageshack.com/a/img924/286/gdXe6V.png)  
--------


* **기본 스킨**
	![기본 스킨](http://files.idg.co.kr/itworld/image/2015/02/00_focuswriter-100565547-orig.jpg)  

* **올드스쿨 스킨**
	![올드스쿨 스킨](https://gottcode.org/focuswriter/screenshots/focuswriter_retro.png)  

* **여러 다양한 스킨**
	![다양한 스킨](https://www.howtoforge.com/images/linux-focuswriter/focuswriter-themes.jpg)  


--------------------------------------
### *타이머 & 알람*

 FocusWriter에는 타이머와 알람기능이 있어 글쓰기 스케줄 관리에 도움을 주며 시간을 정하여 글쓰기에 집중을 할 수 있습니다.  
 
 ![타이머](http://cdn.appstorm.net/windows.appstorm.net/authors/jebakumargodwin/settimer.jpg) 

타이머는 두 가지 모드가 있습니다.   

>지연 시간 설정 - 몇 분 뒤에 알람을 알릴지 설정  
시간 설정 - 지정한 시간에 알람을 알리도록 설정  



![알람](http://cdn.appstorm.net/windows.appstorm.net/authors/jebakumargodwin/alarmdet.jpg)  

알람은 소리로 울리지는 않고 창 오른쪽 아래에 메시지 상자가 나타나는 방식입니다.

-----------------------------------------

### *전체화면 모드*

FocusWriter프로그램기능을 제대로 활용 하기 위해서는 전체화면 모드가 필요하다.  
아래와 같은 방법으로 전체화면 모드를 설정 할 수 있다. 

>Windows: F11 또는 설정 > 전체 화면  
Mac OS X: 설정 > 전체 화면

전체화면 모드를 실행하면 화면에 메뉴와 방해 요소가 모두 제거 되고 종이와 깜빡이는 커서만 남아 있게 된다. 이제 집중해서 글만 작성 하면 된다.
 --------------------------
* TXT, 기본 RTF, 기본 ODT 파일 형식 지원
* 하루 작업 목표 설정 기능
* 스펠링 체킹(맞춤법 기능 – 한국어는 안될듯?) 
* 다양한 테마
* 타자기 소리(옵션)
* 자동 저장(옵션)
* 작업 통계(옵션)
* 맞춤법 검사(옵션)
* 여러 문서 편집 가능
* 세션 관리
* 지능형 따옴표
* 포터블(무설치) 모드(옵션)
* 다국어 메뉴(20개 언어 이상)
* 모든 플랫폼 지원(윈도우,맥용Osx,리눅스)

------------------------------------------------------------------

## 4. **개선점**

