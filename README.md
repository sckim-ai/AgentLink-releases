# AgentLink Releases

AgentLink 데스크톱 앱의 **릴리스 바이너리와 업데이트 매니페스트**만 담는 저장소입니다.
소스 코드는 여기에 없습니다.

## latest.json

앱의 updater가 다음 URL을 읽어 새 버전을 판단합니다.

- 배포: `https://raw.githubusercontent.com/sckim-ai/AgentLink-releases/main/latest.json`
- 검증: `https://raw.githubusercontent.com/sckim-ai/AgentLink-releases/test/latest.json`

`test` 브랜치는 릴리스 전 검증 전용이며 사용자에게 배포되지 않습니다.

설치파일은 각 릴리스의 자산으로 올라가고, `latest.json`은 **고정 태그 URL**을 가리킵니다.
GitHub의 `releases/latest` 판정에는 의존하지 않습니다 — 이 저장소는 커밋이 거의 늘지 않아
모든 릴리스의 `created_at`이 같아질 수 있기 때문입니다.
