직장인 관상 샘플러 - 최종 흐름 버전

동작 방식:
1. 카메라 켜기 버튼을 누릅니다.
2. 관상 분석하기 버튼을 누릅니다.
3. 카메라 화면 위에 "분석중..."이 3초간 표시됩니다.
4. 3초 후 5개 멘트 중 하나가 랜덤으로 재생됩니다.
5. 멘트 자막은 카메라 화면 아래쪽에 직접 표시됩니다.
6. 아래의 Gen Z 스타일 이미지 카드도 결과에 맞게 바뀝니다.

카메라가 안 켜질 때:
브라우저는 보안 때문에 index.html 더블클릭 실행에서 카메라를 막을 수 있습니다.
가장 안정적인 방법은 localhost로 여는 것입니다.

[Mac 기준]

1. office_face_sampler_final 폴더 압축을 풉니다.
2. 터미널을 엽니다.
3. 아래 명령어를 입력합니다.

cd ~/Downloads/office_face_sampler_final
python3 -m http.server 8000

4. Chrome에서 아래 주소로 들어갑니다.

http://localhost:8000

[Windows 기준]

1. office_face_sampler_final 폴더 압축을 풉니다.
2. 폴더 빈 공간에서 Shift + 마우스 오른쪽 클릭
3. "터미널에서 열기" 또는 "PowerShell 창 열기" 선택
4. 아래 명령어 입력

python -m http.server 8000

5. Chrome에서 아래 주소로 들어갑니다.

http://localhost:8000

시연자용 숨겨진 기능:
- 키보드 1~5를 누르면 특정 멘트를 강제로 재생할 수 있습니다.
- 화면에는 샘플 버튼이 보이지 않습니다.

주의:
- index.html과 assets 폴더는 같은 위치에 있어야 합니다.
- assets 폴더 안의 mp3 파일 이름을 바꾸면 코드도 같이 수정해야 합니다.
