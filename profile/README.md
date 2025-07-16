## 🙌🏻 팀원
<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/Yunsung-Jo"><img src="https://avatars.githubusercontent.com/u/135187534?v=4" width="100px;" alt="조윤성"/><br /></a>
      </td>
      <td align="center">
        <a href="https://github.com/Jimin730"><img src="https://avatars.githubusercontent.com/u/108002997?v=4" width="100px;" alt="신지민"/><br /></a>
      </td>
      <td align="center">
        <a href="https://github.com/karlislepark"><img src="https://avatars.githubusercontent.com/u/64067168?v=4" width="100px;" alt="박범진"/><br /></a>
      </td>
      <td align="center">
        <a href="https://github.com/Ogu1208"><img src="https://avatars.githubusercontent.com/u/76902448?v=4" width="100px;" alt="김민아"/><br /></a>
      </td>
      <td align="center">
        <a href="https://github.com/Friox"><img src="https://avatars.githubusercontent.com/u/10986386?v=4" width="100px;" alt="이승훈"/><br /></a>
      </td>
      <td align="center">
        <a href="https://github.com/EndlessMilkyway"><img src="https://avatars.githubusercontent.com/u/26517746?v=4" width="100px;" alt="김영렬"/><br /></a>
      </td>
      <td align="center">
        <a href="https://github.com/chanwonlee"><img src="https://avatars.githubusercontent.com/u/116537544?v=4" width="100px;" alt="이찬원"/><br /></a>
      </td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/Yunsung-Jo">조윤성<br>(PM)</a></td>
      <td align="center"><a href="https://github.com/Jimin730">신지민<br>(PL)</a></td>
      <td align="center"><a href="https://github.com/karlislepark">박범진<br>(DBA)</a></td>
      <td align="center"><a href="https://github.com/Ogu1208">김민아<br>(DevOps)</a></td>
      <td align="center"><a href="https://github.com/Friox">이승훈<br>(CM)</a></td>
      <td align="center"><a href="https://github.com/EndlessMilkyway">김영렬</a></td>
      <td align="center"><a href="https://github.com/chanwonlee">이찬원</a></td>
    </tr>
  </tbody>
</table>

## 🛠️ 조직 전역 컨벤션
### 🌿 Label
| 라벨 | 축약 | 색상 코드 | 설명 |
| --- | --- | --- | --- |
| ✨ feature | feat | #EBE44B | 새로운 기능 또는 기존 기능 관련 |
| 🐞 bug | bug | #E66161 | 버그 관련 |
| 🪏 refactor | refactor | #FAAA34 | 리팩터링 관련 |
| ✅ test | test | #66D143 | 테스트 관련 |
| ⚙️ chore | chore | #5E32BF |  |
| 📝 docs | docs | #44B1EB | 문서 관련 |
| 🙋🏻 question | question | #D4C5F9 |  |

### 🌿 Branch
복잡한 릴리즈 관리가 필요없기 때문에 `GitHub Flow` 전략을 사용합니다.
* `main` : 배포 가능한 상태 또는 일단 구현완료 된 기능 반영
* `feature` : 각자 기능을 개발할 때 사용, Issue 하나 당 하나의 브랜치
* 이외 라벨 : 라벨 별 특성을 반영

`<label>/<issue_number>` 형식을 준수합니다.  
`feature/1-add-layout` 과 같이 작업 내용을 영문으로 설명해도 좋습니다.

### 🌿 Issue
> [!WARNING]
> 하나의 Issue는 하나의 Label만을 가질 수 있습니다.  
> 하나의 Issue에 대해 기능을 추가하고 버그를 수정하는 등 여러 작업을 할 수 없습니다.

| 타입 | 설명 |
| --- | --- |
| ✨ Feature | 새로운 기능을 구현하거나 기존 기능을 수정할 때 생성합니다. |
| 🐞 Bug Report | 발생한 버그를 제보하거나, 버그를 픽스하기 전에 생성합니다. |
| 🪏 Refactor | 코드 구조 개선, 가독성 향상, 중복 제거 등 기능 변화 없이 코드 품질을 높이는 작업 전에 생성합니다. |
| ✅ Test | 테스팅 작업을 구성하고, 수행 전 생성합니다. |
| ⚙️ Chore | 환경 설정, 빌드 환경, 의존성 업데이트 등 비즈니스 로직과 직접적인 관련없는 작업 전에 생성합니다. |
| 📝 Docs | `README.md` 등 코드와 관련한 문서를 작성하기 전 생성합니다. |
| 🙋🏻 Question | 코드 또는 진행 방향 등 특정 멤버에게 궁금한 내용을 질문할 때 생성합니다. |

### 🌿 Commit
`<label>: <작업 내용 설명> (#<issue_number>)` 형식을 준수합니다.  
`feat: 메인 레이아웃 추가 (#1)` 과 같이 사용할 수 있습니다.

### 🌿 PR, Merge
* 모든 인원에게 리뷰요청을 하되, 2개 이상의 Approve를 받아야 Merge할 수 있습니다.
* `main` 브랜치는 잠긴상태로, 직접 push 또는 force-push 할 수 없습니다. 오직 PR을 통해서만 Merge할 수 있습니다.
