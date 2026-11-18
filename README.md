# 스마트탑오피스 광명역 GIDC 홈페이지

광명역 GIDC 공유오피스 소개용 정적 홈페이지입니다. 빌드 과정 없이 HTML/CSS만으로 동작합니다.

## 구성
```
index.html        # 메인 페이지
css/style.css     # 스타일 (색상은 상단 :root 변수에서 변경)
images/           # 공간 사진
```

## GitHub Pages로 게시하기
1. GitHub에서 새 저장소(Repository)를 만들고 이 폴더의 파일을 모두 업로드합니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Source**를 `Deploy from a branch`, Branch를 `main` / `(root)`로 선택하고 Save를 누릅니다.
4. 1~2분 뒤 `https://<계정명>.github.io/<저장소명>/` 주소로 접속할 수 있습니다.

## 정식 도메인 연결 (선택)
Settings → Pages → **Custom domain**에 도메인을 입력하고, 도메인 업체 DNS 설정에서 안내에 따라 레코드를 추가합니다.

## 내용 수정
- 연락처·주소: `index.html`에서 `1666-4250`, `일직로 43`을 검색해 수정합니다.
- 사진 교체: `images/` 안의 같은 파일명으로 덮어씁니다 (가로 900~1000px, JPG 권장).
