# 기여 가이드 (Contributing Guide)

환영합니다! 이 저장소는 대한민국 법령을 구조화하여 GitHub에 등록하는 프로젝트입니다. 누구나 자유롭게 이 프로젝트에 기여할 수 있으며, 아래의 가이드를 참고하여 Issue 생성이나 Pull Request 제출을 진행해 주세요.

저장소 주소: [LAW-OF-REPUBLIC-OF-KOREA](https://github.com/lunalism/LAW-OF-REPUBLIC-OF-KOREA)

---

## 📌 기여 방법

### 1. Issue 생성하기
- **법령 누락**이나 **오탈자**, **형식 오류**를 발견하셨다면 [Issue](https://github.com/lunalism/LAW-OF-REPUBLIC-OF-KOREA/issues) 탭에서 새 이슈를 생성해주세요.
- 제목은 명확하게 작성하고, 본문에는 문제가 발생한 조문이나 위치, 수정 제안을 포함해 주세요.
- 이슈에는 `bug`, `law-name`, `typo` 등의 적절한 라벨을 지정해 주세요.

### 2. Pull Request 보내기
- 저장소를 Fork한 뒤 브랜치를 생성하고 작업을 완료한 후 Pull Request를 보내주세요.
- 각 Pull Request에는 다음 정보를 포함해 주세요:
  - **작업한 조문 범위** (예: 국회법 제24조~제32조)
  - **출처 명시** (예: 국가법령정보센터 기준)
  - **최초 제정 및 개정일 정보 포함 여부**
  - **커밋 메시지 규칙 준수 여부** (아래 참조)

---

## 💬 커밋 메시지 규칙

- 아래 형식으로 작성해 주세요:
  - 국회법 제58조 등록 (최초제정: 1963. 3. 16., 전문개정: 2018. 4. 17., 일부개정: 2019. 4. 16.)

- 각 항목은 가능한 한 **국가법령정보센터의 조문 내역** 기준을 따릅니다.
- 해당 조문에 전문개정이나 일부개정이 없을 경우, 해당 항목은 생략 가능합니다.

---

## 📄 작성 형식

- 모든 조문은 **Markdown(.md)** 형식으로 작성합니다.
- 각 조문은 다음과 같은 구조를 따릅니다:

```markdown
### 제58조(제목)
① 본문의 조문 내용을 작성합니다.  
② 항이 나뉠 경우에는 이렇게 구분합니다.
```

- 부칙은 별도 파일 또는 각 법률 하단에 작성하되, 날짜 및 제정 정보를 명확히 명시합니다.

---

## ✅ 스타일 가이드
원문 형식을 최대한 유지하되, 가독성을 높이기 위한 적절한 줄바꿈과 강조를 허용합니다.

오탈자 없이 원문과 일치하도록 작성하며, 가능한 경우 국가법령정보센터 원문과 대조하여 확인 후 제출해 주세요.

---

## 🙌 기여자 감사
이 프로젝트에 기여해주신 모든 분들께 감사드립니다!
기여자 목록은 추후 CONTRIBUTORS.md에 정리될 예정입니다.
문의나 건의사항은 언제든지 Issue 페이지에 남겨 주세요.

---