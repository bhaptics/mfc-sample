# mfc-sample

- SDK2를 사용한 bHaptics SDK 사용법
  - Developer Portal URL: https://developer.bhaptics.com/
  - Guide document: https://bhaptics.notion.site/Create-haptic-events-using-bHaptics-Developer-Portal-b056c5a56e514afeb0ed436873dd87c6
  
- Visual Studio 설정 (Visual Studio 22 기준)
  - 프로젝트 설정 -> Linker -> General -> Additional Library Directories에 lib 폴더 설정   
  - 예제에는 Lib폴더가 세팅되어 있음   
  
  ![image](https://user-images.githubusercontent.com/5101860/215674377-3480c58a-b6fe-4ffd-aa7a-44eb64e08179.png)   

  - #include "BhapticsSDK2.h" SDK Header 파일 추가
  - #pragma comment (lib, "bhaptics_library.lib") LIB 선언 추가
  
  - 실행 후 실행 폴더(예, x64/Debug)에 lib 폴더의 "bhaptics_library.dll" 파일 추가   
  ![image](https://user-images.githubusercontent.com/5101860/215674927-aa641238-0a35-4c04-ba39-44da93e21a7d.png)   
