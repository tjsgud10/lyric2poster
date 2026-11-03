# Lyric2Poster 실행 및 검증 기록

- 실행 앱: https://lyric2poster-tjsgud10.streamlit.app/
- GitHub: https://github.com/tjsgud10/lyric2poster
- 원본: https://github.com/jahwankoo/lyric2poster-open

교수님이 제공한 MIT 라이선스 템플릿에서 생성한 수업 실습 저장소입니다. 원본 코드와 LICENSE를 유지했습니다. 독자적으로 처음부터 작성한 프로젝트가 아닙니다.

## 확인 완료 (2026-11-03)

- Streamlit Community Cloud 배포 및 Lyric2Poster 화면 표시
- Chart/Song 선택 화면과 직접 입력 모드
- 직접 작성한 예시 곡 Morning Light / Class Demo로 데모 아트 브리프 생성
- 브리프 생성 후 가사 입력란이 비워짐
- 데모 포스터에 곡명과 아티스트 표시
- PNG 다운로드 버튼 표시

## 현재 실행 모드와 한계

API 키를 추가하지 않았습니다. Art director와 image engine은 demo 모드입니다. 브리프는 준비된 예시이며 포스터는 Pillow로 그린 결과입니다. 실제 Claude/FLUX 생성 성공을 의미하지 않습니다.

실제 Claude, FLUX/Hugging Face, Last.fm 수집, Colab 노트북, 이 복사본의 GitHub Actions 실행 및 전체 자동 테스트는 이번 배포에서 검증하지 않았습니다. 원본 README의 테스트 기록은 교수님 원본에 대한 설명입니다. collect-charts 설정은 복사되어 있으나 LASTFM_API_KEY를 설정하지 않았습니다.

배포 성공이 모든 과제 채점 조건 충족을 의미하지는 않습니다.
