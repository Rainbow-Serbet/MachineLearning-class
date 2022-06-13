# 기계학습
## 자동차 번호판 인식 모델

~이 Repo는 수업 발표용으로 제작되었습니다.~

### 사용 라이브러리
1. [numpy](https://numpy.org/)
2. [opencv](https://opencv.org/)
3. [tesseract](https://github.com/tesseract-ocr/tesseract)
4. [matplotlib](https://matplotlib.org/)
 - - -

## 실행방법
[main.py](https://github.com/Rainbow-Serbet/MachineLearning-class/blob/main/main.py)
```py
9 : img_ori = cv2.imread("C:/Users/dudtj/Desktop/test/test.jpg")
```
> 위 코드를 testCase의 파일 경로로 변경

```py
325 : pytesseract.pytesseract.tesseract_cmd = ("C:\Program Files\Tesseract-OCR/tesseract.exe"
```
> 자신의 tesseract.exe 경로로 변경

- - -

### 실행 결과 예제
![2](https://user-images.githubusercontent.com/58870160/173178387-a2d4d703-4729-467e-bd9c-97751a26e472.PNG)
> matplotlib로 중간 과정이 표시되며, 터미널에는 OCR 결과가 출력됨



## Lisence
Apache License   
BSD License   
MIT License
