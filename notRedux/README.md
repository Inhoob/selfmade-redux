# 직접 만드는 redux

## redux가 필요한 이유

component는 재사용성을 높이기 위한 컨셉이다. 그렇다보니 componenet는 외부와의 Dependency가 가능하면 없는 것이 좋다.
그런데 초기의 앱에서 Section에서 startDiscuss,stopDiscuss,removeSection을 사용하기 위해 Index->App->SectionList->Section으로 간단한 앱을 만드는 데에도 4 depth를 들어갈 수 있는데 이게 더 늘어날 경우 dependency가
매우 커지고 버그가 생길 수 있다.
