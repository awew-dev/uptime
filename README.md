# awew-dev/uptime

공개 주소 외부 감시. GitHub Actions가 5분마다 확인하고, 실패하면 워크플로 실패 메일이 간다.

- 대상: console.awew24.com/login, app.awew24.com, api.awew24.com/actuator/health, awew24.com
- 공개 저장소다(공개 저장소는 Actions 시간이 무료). 이미 공개된 주소만 적는다.
- 클러스터 안의 경보(Alertmanager)와 별개다. 주 서버가 통째로 멈춰도 이 감시는 돈다.
