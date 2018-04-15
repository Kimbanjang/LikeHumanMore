# Like-Human More
이 코드는 포트폴리오를 보강하기 위한 샘플코드 입니다.
### Child (Lua)
Parent 를 통한 Order 가 없어도 동작 확인이 가능 하도록 WOW Addon 형태로 구성 되었습니다.<br />
Generic API 중 액션에 관련된 것은 프로텍터가 걸려 있기 때문에, Live 서버에서 확인을 위해 다음 방법을 제안 합니다.
```
Solution 1 : Hardware Breakpoint 재설정과 Instruction Pointer 변경으로 Lua Unlock
Solution 2 : Keysend 사용
Solution 3 : 지시에 맞춰 직접 누른다.. 엄진근!
```
### Parent (Lua)
Automation 을 위해서는 Memory Read/Write 가 필요하기 때문에 Live 서버에서 확인이 어렵습니다.<br />
따라서 BigWigs/DBM 과 같이 오퍼레이팅 시스탬으로 열화시켜 동작 여부를 확인 하는 수준으로 구성 하였습니다.
```
내가 AI 가 된양 시키는 데로 움직여서 제대로 판단 했는지 확인 하겠다는 말
```
### Profile Editor (C++ or C#)
프로파일을 만들수 있는 Storyboard 형식의 GUI 에디터(유행에 따라..).
```
샘플 단계라 프로파일의 암호화가 필요하지 않기 때문에 일단은 하드코딩 하고, 에디터 제작 자체는 보류
```
