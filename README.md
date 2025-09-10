# .NET_Template  
## 0. 실습 환경 셋팅  
- [GitHub](https://github.com/pmj-chosim/.NET_Template)에 접속 후, 로그인하세요.  
- 레포지토리를 fork하세요.
  <img width="1307" height="338" alt="image" src="https://github.com/user-attachments/assets/d6c4a558-68fc-4d79-bc1d-db252c1ba63b" />  
  <br>
- create fork 버튼을 눌러 포크합니다.
<img width="915" height="557" alt="image" src="https://github.com/user-attachments/assets/01370aa5-9f7d-405f-b58f-0e2368ce775b" />  <br>  
- fork된 레포지토리에서 code 버튼을 누른 후, + 버튼을 누릅니다.
<img width="830" height="312" alt="image" src="https://github.com/user-attachments/assets/c18b6b50-4fa2-44db-9b74-970eda2ae708" />   <br>
- "+" 버튼을 눌러 생성된 가상 VSCode 환경에 GitHub Copilot을 설치합니다.    
  - 확장 버튼을 누른 후, github copilot을 검색한 후 설치합니다.    
    <img width="967" height="547" alt="image" src="https://github.com/user-attachments/assets/ed253882-1579-4bde-a254-90ebbd9258bd" />  <br>
- .NET version을 터미널에서 확인합니다. `dotnet --version` 명령어를 입력합니다.
 <img width="842" height="167" alt="image" src="https://github.com/user-attachments/assets/aeae0236-0720-4845-900f-199cfcfbcff5" />  <br>  

-----

참고) [Visual Studio에서 GitHub Copilot 설치](https://learn.microsoft.com/ko-kr/visualstudio/ide/visual-studio-github-copilot-install-and-states?view=vs-2022)  

-----

<br>  

## 1. 2~5 모듈 실습에서 zip 폴더 내용들을 붙인 후, 아래 명령어들을 통해 솔루션을 추가하세요.

0) C# Dev Kit 설치
<img width="1596" height="716" alt="image" src="https://github.com/user-attachments/assets/1b5fdbd9-8d5b-4b26-b374-35db88baf171" />


1) `cd AccelerateDevGHCopilot`

```bash
dotnet new sln -n AccelerateDevGHCopilot
dotnet sln AccelerateDevGHCopilot.sln add src/Library.ApplicationCore/Library.ApplicationCore.csproj
dotnet sln AccelerateDevGHCopilot.sln add src/Library.Infrastructure/Library.Infrastructure.csproj
dotnet sln AccelerateDevGHCopilot.sln add src/Library.Console/Library.Console.csproj
dotnet sln AccelerateDevGHCopilot.sln add tests/UnitTests/UnitTests.csproj
```

<img width="1490" height="767" alt="image" src="https://github.com/user-attachments/assets/0c00b6f0-cfc6-4655-8415-d571da1d45f8" />

