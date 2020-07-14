## 추억의 오락실 게임 만들기
: 파이썬 기본을 공부하고 시간이 지났지만 배운 것을 토대로 알고리즘을 풀거나 장고를 사용할 때 문법 등을 자유자재로 사용하지 못했다.\
=> 그래서 pygame을 이용해 게임을 만들면서 python을 실전에 적용해보고자 시작하게 되었다.
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
1. 배경 : 640 * 480 (세로 * 가로) - background.jpg
2. 캐릭터 : 70 * 70 - character_real.png
3. 똥 : 70 * 70 - enemy_real.png
#### [게임 이미지 다운]
1. 배경\
: https://www.freepik.com/free-photo/design-space-paper-textured-background_3220799.htm#page=1&query=paper&position=0
2. 캐릭터\
: https://www.freepik.com/free-vector/pack-pugs-with-lovely-style_1353886.htm#page=1&query=shit&position=6
3. 똥\
: https://www.freepik.com/free-vector/funny-poop-sticker-collection_1318153.htm#page=1&query=shit&position=0

#### [똥 피하기 게임 완성본]
<img src="./poop.gif">

### 오락실 팡 게임
#### [게임 조건]
1. 캐릭터는 화면 아래에 위치, 좌우로만 이동 가능
2. 스페이스를 누르면 무기를 쏘아 올림
3. 큰 공 1개가 나타나서 바운스
4. 무기에 닿으면 공은 작은 크기 2개로 분할, 가장 작은 크기의 공은 사라짐
5. 모든 공을 없애면 게임 종료 (성공)
6. 캐릭터는 공에 닿으면 게임 종료 (실패)
7. 시간 제한 99초 초과 시 게임 종료 (실패)
8. FPS는 30으로 고정 (필요시 speed 값을 조정)

#### [게임 이미지]
1. 배경 : 640 * 480 (가로 * 세로) - background.jpg
2. 무대 : 640 * 50 - state.png
3. 캐릭터 : 33 * 60 - charater.png
4. 무기 : 20 * 430 - weapon.png
5. 공 : 160 * 160, 80 * 80, 40 * 40, 20 * 20 - balloon1.png ~ balloon4.png

#### [게임 이미지 다운]
1. 배경\
: https://www.freepik.com/free-vector/arcade-game-world-pixel-scene_4815143.htm#query=arcade-game-world-pixel-scene&position=8
2. 무대\
: https://www.freepik.com/free-vector/urban-city-day-time-background_4708004.htm#page=5&query=brick&position=47
3. 캐릭터\
: https://opengameart.org/content/custom-sprites-for-the-crystal-palace-0
4. 무기 머리 부분\
: https://www.freepik.com/free-vector/weapon-icons-set_3924829.htm#page=1&query=arrow%20weapon&position=7
5. 무기 몸체 부분 (와이어)\
: https://www.freepik.com/free-vector/barbed-wire-realistic-illustration-separate-elements-barbed-wire_3586280.htm#page=1&query=wire&position=37
6. 공\
: https://www.freepik.com/free-vector/colored-bubbles_808278.htm#page=2&query=bubble&position=18