# Format String Bug
프로그램에서 출력 함수(printf, fprintf, sprintf 등)를 사용할 때
포맷 문자열(format string)에 사용자 입력값을 그대로 전달함으로써,
메모리 내용 노출이나 임의 메모리 접근이 가능해지는 취약점을 의미하며,
이를 포맷 스트링 버그(Format String Bug) 라 한다.