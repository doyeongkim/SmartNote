# SmartNote - 똑똑이 노트 (해커톤 프로젝트)

<br>

갖고있는 이미지 또는 찍은 사진에 담긴 텍스트를 추출하여 복사해서 바로 메모로 작성할 수 있고 특정언어로 번역하여 저장할 수 있는 앱

Simple!  Take a photo -> App will extract text from photos -> Copy text to Memo -> Can translate it to other language.

<p align="center">
<img width="500" alt="스크린샷 2019-09-14 오후 8 06 19" src="https://user-images.githubusercontent.com/29372705/64907273-240e6700-d72b-11e9-9f48-fd4f1c892c73.png">
</p>
</div>

- 참여 인원 : iOS 2명

- 담당 구현 파트:
  - Google Cloud Vision API (OCR)를 통해 사진에 담겨있는 텍스트를 감지하고 추출 기능
  - 메모 리스트 및 디데일 뷰 UI 구현
  - 'DropDown' 라이브러리를 사용해 번역할 언어 드롭다운 버튼 구현
  - 메모 찾기, 삭제(CoreData), 공유 기능 구현

- 사용 기술 : Swift, Google Cloud Vision API, Kakao 번역 API, CoreData, Git, GitHub

- 시연 영상 : https://www.youtube.com/watch?v=c3-iKhdcI7s&t=0s
