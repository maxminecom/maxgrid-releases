# MaxGrid 릴리스 / MaxGrid releases

맥스그리드(MaxGrid)의 **공식 릴리스 파일 보관소**예요. npm에 올라간 패키지와 같은 파일을 버전마다 보관해서, 스토어나 CDN을 쓸 수 없을 때도 내려받을 수 있게 해요. 소스 코드 저장소는 아니에요.

This repository keeps the **official release files** of MaxGrid for every version: the same files that are published to npm, so you can still download them when the store or the CDN is unavailable. It is not a source repository.

## 내려받기 / Download

[Releases](../../releases) 페이지에서 버전을 고르고 `Assets`에서 받아요.

- `maxgrid-<버전>-all.zip`: 모든 패키지와 체크섬을 한 번에
- `maxgrid-*.tgz`, `@maxgrid` 패키지별 파일: `npm i ./파일.tgz`로 설치
- `SHA256SUMS`: 받은 파일 확인용

## 설치 / Install

```bash
# npm에서 (가장 간단해요)
npm i maxgrid

# 이 보관소의 파일로
unzip maxgrid-<버전>-all.zip
sha256sum -c SHA256SUMS
npm i ./maxgrid-<버전>.tgz
```

프레임워크 래퍼는 `@maxgrid/react`, `@maxgrid/vue`, `@maxgrid/angular`로 따로 설치해요.

## 라이선스 키 / License key

키가 없으면 평가 모드로 동작해요(하단 워터마크, 콘솔 경고). 운영 환경에서는 구입하신 라이선스 키를 설정해요. 키 검증은 번들 안에서 끝나서 서버와 통신하지 않아요. 구입·갱신·약관은 스토어에서 안내해요.

Without a key the grid runs in evaluation mode. Set your license key for production. Key checks run inside the bundle and do not contact a server.

## 링크 / Links

- 문서 / Docs: https://grid.maxmine.com/docs/
- 스토어 / Store: https://store.maxmine.com/p/grid
- 문의 / Contact: desk@maxmine.com

© 주식회사 맥스마인. 이 보관소의 파일에는 제품 사용권이 적용돼요.
