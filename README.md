# Face-API-javascript
Tensor FLow를 기반으로 구축된 Face API JS 라이브러리를 사용하여 얼굴인식을 설정하겠습니다.
먼저 Face API 라이브러리를 사용해서 같은 폴더에 있는 labeled_images 폴더에 각각의 객체를 넣고
얼굴 사진을 넣어 얼굴을 학습하도록 합니다. 라이브러리 모델로 얼굴을 학습하고 난후에는
html코드를 사용해서 웹을 만듭니다. 그리고 이미지나 파일등을 불러올수 있도록 자바스크립트 코드를 작성합니다.
html코드에는 Face-API.min코드와 script파일이 수행되도록 작성하고 script에는 불러온 이미지나 영상을 보고
labeled_images 에서 학습한 모델을 바탕으로 일치하는 얼굴이 있는지 인식합니다.
