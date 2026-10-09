# Tezcatl 페이지

groovin.io 에서 서비스하는 Tezcatl 의 약관·개인정보 처리방침·지원 페이지다.

| 파일 | 주소 | 쓰이는 곳 |
| --- | --- | --- |
| `privacy-policy.html` | `https://groovin.io/tezcatl/privacy-policy` | 홈의 Tezcatl 카드, Play Console 의 개인정보처리방침 URL |
| `privacy-policy-ko.html` | `https://groovin.io/tezcatl/privacy-policy-ko` | 영문 페이지의 언어 버튼 |
| `terms.html` | `https://groovin.io/tezcatl/terms` | 홈의 Tezcatl 카드 |
| `terms-ko.html` | `https://groovin.io/tezcatl/terms-ko` | 영문 페이지의 언어 버튼 |
| `support.html` | `https://groovin.io/tezcatl/support` | 홈의 Tezcatl 카드 |

홈에서 이어지는 링크는 영문 페이지뿐이다. 한글 페이지로는 주소를 직접 입력하거나, 영문 페이지의
메인 타이틀 오른쪽에 있는 언어 버튼(`English` · `한국어`)으로 들어간다. 버튼은 `css/style.css` 의
`.page-title-row` 와 `.lang-switch` 를 쓰고 두 쪽이 서로를 가리키므로, 페이지를 새로 만들면 양쪽
링크를 모두 맞춘다.

영문이 원문이고 한글이 그 번역이다. **한쪽만 고치면 두 언어의 내용이 갈라지므로 반드시 함께 고친다.**

문서의 원문은 Tezcatl 앱 레포의 `PRIVACY_POLICY_{en,ko}.md` 와 `TERMS_OF_USE_{en,ko}.md` 다.
앱 레포에서 문서를 고치면 여기 네 페이지도 같은 내용으로 옮긴다.

약관은 앱 안에서도 보여 준다. 그 문구는 앱 레포의 `app/src/main/res/values/strings.xml` 과
`values-en/strings.xml` 의 `terms_intro`·`terms_section_*`·`terms_confirmation` 에 있고,
여기 페이지와 같은 내용이어야 한다. 셋(문서·한국어 문자열·영어 문자열) 중 하나만 고치면 어긋난다.

개인정보 처리방침을 고칠 때는 페이지 첫머리의 시행일도 함께 올리고, Play Console 의 데이터 보안
선언과 앱 레포 `docs/PLAY_STORE.md` 의 등록정보 문구가 같은 사실을 말하는지 확인한다.

현재 반영된 이용약관 및 개인정보 처리방침 시행일: 2026년 10월 9일
