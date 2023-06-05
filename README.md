# V1-NextJs
NextJs-Study

#git commit rule
1. 커밋 메시지 구조
기본적으로 커밋 메시지는 아래와 같이 제목/본문/꼬리말로 구성한다.
'''
Type : Subject
body
'''

footer
2. 커밋 종류
'''
- feat 		: 새로운 기능 추가
- fix 		: 버그 수정
- docs 		: 문서 수정
- style 	: 코드 formatting, 세미콜론(;) 누락, 코드 변경이 없는 경우
- refactor 	: 코드 리팩토링
- test 		: 테스트 코드, 리팽토링 테스트 코드 추가
- chore 	: 빌드 업무 수정, 패키지 매니저 수정
'''

3. 제목
제목은 50자를 넘기지 않고, 마침표를 붙이지 않는다.
제목에는 위 커밋 종류를 함께 쓴다.
과거시제를 사용하지 않고 명령조로 작성한다.
제목과 본문은 한 줄 띄워 분리한다.
제목의 첫 글자는 반드시 대문자로 쓴다.
제목이나 본문에 이슈 번호(가 있다면) 붙여야 한다.

4. 본문
선택사항이기에 모든 커밋에 본문 내용을 작성할 필요는 없다.
한 줄에 72자를 넘기면 안된다.
어떻게(How)보다 무엇을, 왜(What, Why)에 맞춰 작성한다.
설명뿐만 아니라, 커밋의 이유를 작성할 때에도 쓴다.

5. Footer
선택사항이기에 모든 커밋에 꼬릿말을 작성할 필요는 없다.
Issue Tracker ID를 작성할 때 사용한다.
