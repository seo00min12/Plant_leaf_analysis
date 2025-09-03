### https://seolog-12.tistory.com/16 에서 해당 프로젝트의 완료 보고서를 작성하였습니다



데이터는 [Data for: Identification of Plant Leaf Diseases Using a 9-layer Deep Convolutional Neural Network](https://data.mendeley.com/datasets/tywbtsjrjv/1) - Mendeley Data 에서 가져왔습니다


jupyter notebook에서 작성하였고 python언어를 통해 딥러닝 코드를 만들었숩나다

1. Split_Data.ipynb
   => 해당 파일은 훈련데이터, 검증데이터, 평가데이터로 폴더를 나누어 거기에 이미지를 담는 과정이 들어있는 코드입니다 방대한 이미지 파일이 있기에 수작업으로는 한계가 있어 코드로 작성하여 분류하였습니다


2. CNN.ipynb
   => 해당 파일은 해당 프로젝트의 메인 코드입니다 분할 된 데이터를 학습하고 평가할 모델을 만드는 과정이며 Pytorch의 CNN을 이용하였습니다
   
3. baseline.pt
   => 학습이 완료된 모델이 저장된 파일입니다 해당 모델은 CNN.ipynb를 통해 만들었으며 CNN.ipynb에서 평가정확도를 측정할때 불러옵니다
