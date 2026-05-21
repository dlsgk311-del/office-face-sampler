직장인 관상 샘플러 - 카메라 복구 + 오디오 수정 버전

이번 버전의 기준:
- 카메라가 정상 작동하던 office_face_sampler_final 버전을 기준으로 복구했습니다.
- 카메라 관련 로직은 기존 정상 버전의 방식으로 되돌렸습니다.
- 오디오만 iPhone 대응 방식으로 수정했습니다.

오디오 수정:
- assets/sound1.mp3 ~ sound5.mp3 영문 파일명 사용
- HTML에 audio 태그 미리 배치
- 관상 분석하기 버튼 클릭 즉시 play()
- 3초 뒤 play() 재호출 없음
- 각 mp3 안에 짧은 찰칵음 + 약 3초 대기 + 실제 멘트 포함

GitHub 업데이트:
1. 이 ZIP 압축을 풉니다.
2. 기존 저장소 루트에 아래 3개를 모두 덮어쓰기 업로드합니다.
   - index.html
   - README.txt
   - assets 폴더 전체
3. Commit changes를 누릅니다.
4. 테스트 링크 뒤에 ?v=200 을 붙여 캐시를 피하세요.

예:
https://사용자명.github.io/저장소명/?v=200
