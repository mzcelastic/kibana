# 엘라스틱 사용자 사전 관리 플러그인

사용자 사전 등록, 버전 관리 등 기능을 제공합니다.

## 사전 요구사항

- 키바나가 설치된 시스템
- Node.js (플러그인 개발 시 필요)
- Git (소스 코드 다운로드 시 필요)

## 설치

1. **플러그인 다운로드**

   Git을 사용하여 플러그인 소스 코드를 다운로드합니다.

   git clone <플러그인 Git 저장소 URL>
   cd <플러그인 디렉토리>


2. **플러그인 설치**

    /path/to/kibana/bin/kibana-plugin install file:///path/to/plugin.zip


3. **플러그인 삭제**

    /path/to/kibana/bin/kibana-plugin remove <플러그인 이름>