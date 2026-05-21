직장인 관상 샘플러 - ASCII 파일명 소리 수정 버전

이번 수정 핵심:
1. 화면/UI는 유지했습니다.
2. 오디오 파일명을 전부 영문으로 바꿨습니다.
   - assets/sound1.mp3
   - assets/sound2.mp3
   - assets/sound3.mp3
   - assets/sound4.mp3
   - assets/sound5.mp3
3. 어제 성공했던 샘플러처럼 <audio> 태그를 HTML에 미리 넣었습니다.
4. 관상 분석하기 버튼을 누르는 즉시 audio.play()를 실행합니다.
5. 3초 뒤에는 play()를 다시 호출하지 않습니다.
6. 각 mp3 파일 안에 짧은 찰칵음 + 약 3초 대기 + 실제 멘트가 들어 있습니다.

GitHub 업데이트:
- index.html
- README.txt
- assets 폴더 전체

위 3개를 반드시 모두 덮어쓰기 업로드하세요.

테스트:
기존 링크 뒤에 ?v=100 을 붙여서 캐시를 피하세요.

예:
https://사용자명.github.io/저장소명/?v=100
