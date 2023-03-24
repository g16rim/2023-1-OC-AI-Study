# 2주차 WIL
## matplotlib
세심하게 그리고 싶을 때
### import할 때
- import matplotlib.pyplot as plt
### 사용법
- plt.plot가로축, 세로축): 선 그래프
- plt.title('title'): 제목 설정
- plt.bar(가로축, 세로축): 바 그래프
- plt.subplots(rows, cols): 그래프 여러 개 그리고 싶을 때
- plt.figure(figsize=(가로, 세로)): 크기 지정
- plt.scatter(가로축, 세로축): 점들이 모여있음
- plt.pie(숫자, labels=리스트, explode=리스트)
- plt.show()
## seaborn
빨리 간단하게 그리고 싶을 때
### import할 때
- import seaborn as sns
### 사용법
- sns.load_dataset("제목")
