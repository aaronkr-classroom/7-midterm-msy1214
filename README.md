[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/SmNw8oFb)
# 중간고사 시험 안내

`hansan.c` 파일을 만들 때, 우리가 사용할 수 있는 모든 비트 패턴을 사용하지 않았습니다. 7번째(마지막) 비트는 사용되지 않았습니다.

1. 기존의 `hansan.c` 파일을 수정하여, 여러분이 선택한 새로운 명령어 하나를 추가하세요.
2. 코드가 실행될 때 올바른 메시지가 출력되도록 전체 코드를 업데이트하세요. 이를 위해 다음 작업을 수행해야 합니다:
  - 새로운 `#define` 상수를 추가하기
  - `showStatus()` 함수를 수정하기
  - `printMenu()` 함수를 수정하기
  - `switch()` 문을 수정하기
3. 추가로, 메인 프로그램에서 생명 점수를 저장할 변수를 만드세요. 변수 이름은 `fleet_power` 또는 `hp`로 하고, 초기값은 예를 들어 100으로 설정하세요. 그리고 `switch()` 문 안에서 다음을 수행하세요:
  - 함선이 피해를 받을 때마다 일정한 `H`를 감소시키세요 (예: -10)
  - 함선이 `"부상병 후송"`을 수행할 때마다 일정한 `HP`를 증가시키세요 (예: +5)
  - `switch()` 문이 끝나기 전에 (`showStatus(fleet)` 호출 전, 그리고 `while()` 루프가 끝나기 전에), `HP`가 0 이하인지 확인하세요.
만약 `HP`가 0 이하라면, `"You are dead. Game Over"` 메시지를 출력하고 게임을 종료하세요.
