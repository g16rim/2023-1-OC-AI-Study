### WIL5

#### 전처리
- null값 삭제
- df.dropna(inplace=True)

#### Scaling
- 단위 통일
- scaler = StandardScaler()
- scaler.fit_transform() -> train dataset에만 상
- scaler.transform()

#### 학습
- Tree 모델
- classifier.fit(x, y)

#### 예측
- classifier.predict(x)

#### 정확도 계산
- accuracy_score(예측 y, 실제 y)
