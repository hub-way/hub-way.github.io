## Git hub를 이용하여 까페에 코드 관련 글을 작성하는 법을 연습.

몇가지 md 파일의 문법도 살짝 보았다. 
무엇보다도 지금은 
Git-hub 에서 파일을 쉽게 작성하고 보기 좋게
작성하는 법을 익히는 것이다. 
그 처음으로 코드를 작성하는 것이다. 
몇 일 전에 파이썬 연습 했던 코드를 이용하여 기록 해본다. 

colab 에서 파이썬 으로 구현한 코드의 일부이다. 
본 코드는 아래의 링크에저장되어 있는 코드를 
Colab 에 마운트 하여 note로 작업하는 과정이다. 

**Demo** https://colab.research.google.com/drive/19NoNynRfAua543DPfkZnUjbEik5bARbB?hl=ko

'''
#***************************************************************
print("{:*^50}".format(" januaryTemperature.jpynb ") )
print("@ Title       :                            ")
print("@ Writer      : A71010_문 기 정            ")
print("@ Description :                            ")
print("Jupyter 코딩연습. 1월 최대온도/최저 온도 산출 ")
print("@name :januaryTemperature.jpynb           ")
print("@ 2026 11.08 : Create Project ....         ")
print("{:*^50}".format("") )
#***************************************************************

MAX_TEMPERATURE = -100

drive.mount('./my_drive', force_remount=True)
original_dir = os.getcwd()
print(original_dir)

f = open ('./my_drive/MyDrive/Colab Notebooks/t.csv', 'r', encoding='cp949')
data = csv.reader(f, delimiter=',')
print(data)
'''


