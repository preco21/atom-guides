## Core Settings

> :grey_question: 이 설정은 텍스트 편집과 관계 없는 동작에 관한 Atom Editor의 코어 설정입니다. 몇몇 패키지는 해당 패키지만의 추가적인 설정을 가지고 있을 수 있으며 `Package list`의 패키지 카드에서 찾을 수 있습니다.

### Allow Pending Pane Items (패널 아이템 미리보기 허용)

트리뷰에서 파일을 한 번 클릭 했을 때, 아이템을 탭에 추가하지 않고 미리보기 형태로 이전 패널과 겹쳐 보여줍니다.

### Audio Beep (비프음)

어떤 특정한 동작을 실행시키지 못했거나 결과가 없을 때 시스템 비프 사운드를 재생합니다.

### Auto Hide Menu Bar (메뉴 막대 자동 숨기기)

자동으로 창 상단의 메뉴 막대를 숨기고, Alt키를 눌렀을 때만 토글합니다. 이 기능은 Windows와 Linux에서만 지원합니다.

### Automatically Update (자동 업데이트)

새로운 릴리즈를 사용할 수 있을 때 Atom을 자동으로 업데이트 합니다.

### Close Empty Windows (빈 창 닫기)

윈도우가 탭이나 패널을 하나도 열고 있지 않을 때, `탭 닫기 (Close Tab)` 커맨드가 입력되면 윈도우를 닫습니다.

### Remove Empty Panes (빈 패널 닫기)

패널의 마지막 탭이 닫혔을 때, 그 패널도 같이 닫습니다.

### Exclude VCS Ignored Paths (VCS에서 무시된 경로 제외하기)

현재 프로젝트의 VCS 시스템에서 무시된 파일과 디렉토리가 몇몇 `fuzzy finder`와 `find and replace` 같은 패키지에서 무시됩니다. 예를 들어 Git을 사용하는 프로젝트에서 이러한 경로가 .gitignore 파일에 기재되어 있는 경우가 있습니다. 각각의 패키지들은
VCS에서 무시된 파일과 경로에 대한 추가적인 설정을 제공할 수도 있습니다.

### File Encoding (파일 인코딩)

파일을 읽거나 작성할 때 사용할 기본 문자 세트를 지정합니다.

### Follow Symlinks (심링크 따라가기)

파일을 찾거나 `fuzzy finder`로 열 때 심링크를 따라갑니다.

**참고:** 심링크는 `심볼릭 링크`의 약자이며 흔히 보는 `바로가기`와 같은 일을 합니다.

* [심볼릭 링크](https://ko.wikipedia.org/wiki/%EC%8B%AC%EB%B3%BC%EB%A6%AD_%EB%A7%81%ED%81%AC)

### Ignored Names (무시될 파일과 경로)

Glob 패턴 문자열로 이루어진 리스트입니다. 이 패턴에 일치하는 파일과 디렉토리는 몇몇 `fuzzy finder`와 `find and replace` 같은 패키지에서 무시됩니다. 각각의 패키지들은 무시될 파일과 경로에 대한 설정을 제공할 수도 있습니다.

### Open Empty Editor On Start (시작시 빈 에디터로 열기)

자동으로 아무것도 열리지 않은 빈 에디터로 시작합니다.

### Packages With Keymaps Disabled (단축키 설정을 비활성화할 패키지 리스트)

이 리스트에 추가된 패키지는 해당 패키지에서 기본으로 제공하는 단축키 설정이 비활성화됩니다.

예시: `activate-power-mode, emmet, expose`

### Project Home (프로젝트 홈)

프로젝트가 위치해야 할 경로입니다. 패키지 생성기로 만드는 패키지들은 모두 기본적으로 이 경로를 기준으로 생성됩니다.

### Send Telemetry to the Atom Team (Atom 팀으로 사용 정보 보내기)

Atom을 더 좋게 만들기 위해 사용 정보와 예외 리포트를 Atom 팀으로 보낼 수 있도록 허용합니다.

### Warn On Large File Limit

메가바이트 단위의 지정한 용량보다 더 높은 파일을 열 때 알림을 표시합니다.
