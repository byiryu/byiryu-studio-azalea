# byiryu-studio-azalea

Azalea 아임웹 구축 — **의뢰인 검토용 시안 배포 저장소.**

- 🔴 **로컬이 SoT.** 원본 = `project-imweb/projects/azalea/design/boards/mockups/` (규칙 3)
- 이 저장소는 **배포 대상**일 뿐이다. 여기서 직접 수정하지 않는다.
- 🔴 **배포 대상은 목업 HTML 뿐.** `notes.md` · `wireframe/` · 개발용 허브는 **절대 올리지 않는다.**
  (`notes.md` 에 "가격 전부 가상값" 등 의뢰인이 보면 안 되는 내용이 있다)
- 전 페이지 `noindex,nofollow` + `robots.txt Disallow: /`
- 루트 `index.html` 은 **빈 랜딩** — 의뢰인 목록·프로젝트 목록을 노출하지 않는다.

## 배포
`project-imweb/_deploy/publish.sh` 로 목업만 골라 복사·푸시.
