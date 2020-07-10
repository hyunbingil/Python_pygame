## 추억의 오락실 게임 만들기
: 파이썬 기본을 공부하고 시간이 지났지만 배운 것을 토대로 알고리즘을 풀거나 장고를 사용할 때 문법 등을 자유자재로 사용하지 못했다.\
=> 그래서 pygame을 이용해 게임을 만들면서 python을 실전에 적용해보고자 시작하게 되었다.
> c++이랑 더이상 헷갈리지 말자 ㅠ
### 기본기
- 배경
- 캐릭터
- 키보드 이벤트
- FPS
- 충돌 처리
- 텍스트
- 게임 개발 프레임
### 똥 피하기 게임
: 하늘에서 떨어지는 똥 피하기 게임을 만드시오.
#### [게임 조건]
1. 캐릭터는 화면 가장 아래에 위치, 좌우로만 이동 가능
2. 똥은 화면 가장 위에서 떨어짐. x 좌표는 매번 랜덤으로 설정
3. 캐릭터가 똥을 피하면 다음 똥이 다시 떨어짐
4. 캐릭터가 똥과 충돌하면 게임 종료
5. FPS는 30으로 고정
#### [게임 이미지]
1. 배경 : 640 * 480 (세로 * 가로) - background.png
2. 캐릭터 : 70 * 70 - character.png
3. 똥 : 70 * 70 - enemy.png
#### [게임 이미지 다운]
1. 배경\
: https://www.freepik.com/free-photo/design-space-paper-textured-background_3220799.htm#page=1&query=paper&position=0
2. 캐릭터\
: https://www.freepik.com/free-vector/pack-pugs-with-lovely-style_1353886.htm#page=1&query=shit&position=6
3. 똥\
: https://www.freepik.com/free-vector/funny-poop-sticker-collection_1318153.htm#page=1&query=shit&position=0

### 프로젝트(오락실 팡 게임)