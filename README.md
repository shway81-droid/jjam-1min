# ⏱ 짬짬이 1분 수업 — 발행 저장소

**주소:** https://shway81-droid.github.io/jjam-1min/

이 저장소에는 **사이트 소스가 없습니다.** 발행만 합니다.

## 왜 이렇게 되어 있나

짬짬이 여섯 사이트의 소스는 모두 한 저장소에 모여 있습니다.

> **소스:** https://github.com/shway81-droid/jjam-classroom → `1min/` 폴더

그런데 GitHub Pages 주소는 **저장소 이름**에서 나옵니다. `github.io/jjam-1min/` 의
`jjam-1min` 이 곧 이 저장소 이름입니다. 그래서 소스는 한곳에 모으고, 발행만 이름이
맞는 저장소가 맡습니다. 자매 사이트(`jjam` · `jjam-quiz` · `jjam-video` ·
`jjam-story` · `jjam-word`)도 모두 같은 구조입니다.

## 고칠 일이 있으면

**여기서 고치지 마세요.** 발행이 상류 내용으로 덮어씁니다.

```
https://github.com/shway81-droid/jjam-classroom  →  1min/
```

차시를 추가하는 방법은 `1min/README.md` 에 있습니다.

## 언제 반영되나

- 상류 `1min/` 이 `main` 에 머지되면 곧바로 (상류가 `classroom-published` 신호를 보냅니다)
- 신호가 막히더라도 **하루 한 번 크론**(KST 04:30경)이 안전망입니다
- 지금 당장 반영하려면 Actions 탭에서 `발행 — jjam-classroom 에서 받아 배포` → Run workflow

## 무엇을 서비스하나

교과서 한 차시를 1분 세로 영상으로 압축해 **교과서 진도 순서대로** 골라 쓰는 사이트입니다.
영상은 유튜브(`Shway Song` 채널)에 있고 이 저장소는 영상 ID만 듭니다.
설치·로그인 없이 브라우저에서 바로 동작하고, 목록과 검색은 오프라인에서도 됩니다.
