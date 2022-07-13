> 기존 맥과 M1의 결정적 차이 맥용으로 개발한 애플 칩셋
> 

### 용어

---

|  Rosetta | intel 프로세서가 장착된 Mac용으로 제작된 앱을 Apple Sillcon이 장착된 Mac에서 사용 가능 |
| --- | --- |
|  HomeBrew | Mac에서 필요한 패키지를 설치하고 관리하는 맥용 패키지 관리자 |
|  Oh My ZSH | shell 프로그램 |
|  Watchman | 특정 폴더나 파일을 감시하다가 변화가 생기면 
특정 동작을 실행하도록 설정하는 역할
(ex React-Native에서는 소스코드의 추가, 변경이 발생하면 다시 빌드하기 위해 Watchman을 사용하고 있습니다. |
|  cocoapods | iOS 개발에 사용되는 의존성 관리자 |
|  npm |  |

- React Native 환경 구축
    
    <aside>
    👉🏻 HomeBrew를 먼저 설치해보자~
    
    </aside>
    
    1. 터미널에서 아래 명령어 실행
    
    ```jsx
    /bin/bash -c "$(curl -fsSL [https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh](https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh))"
    ```
    
    1. 5~10분 기다리면  Next Steps이 나온다 그대로 터미널에 입력!
    
    ![스크린샷 2022-07-13 오후 4.47.42.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/938bf95c-fab3-4726-9774-51207e1d589d/스크린샷_2022-07-13_오후_4.47.42.png)
    
    1. 잘 설치 되었는지 확인 하기 버전이 잘 나오면 설치 완료!
        
         `brew --version`
        
    
    ---
    
    <aside>
    👉🏻 **Node js** 설치
    
    </aside>
    
    1. 터미널에서 아래 명령어 실행
        
        `brew install node`
        
    2. node와 node설치시 같이 설치되는 npm이 잘 설치되었는지 확인하자
        
        `node --version`
        
        `npm --version`
        
    
    ---
    
    <aside>
    👉🏻 **Watchman** 설치
    
    </aside>
    
    1. 터미널에서 아래 명령어 실행
        
        `brew install node`
        
    2. node와 node설치시 같이 설치되는 npm이 잘 설치되었는지 확인하자
        
        `node --version`
        
        `npm --version`
