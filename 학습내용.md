# llm_study
- 강의 출처 : https://www.youtube.com/watch?v=-vnxFKHmKjc&t=310s

## llm
- 텍스트 생성, 분류, 번역, 질의 응답
- 필요한 파라미터 수억개(bias + weight * x)
- transformer 구조
  > 문장에서 단어 하나씩 가려나가면서 가린부분을 label로 인식하여 학습을 해 나간다.
- ex) chatgpt

## foundation model 
- 범용성이 높고 다양한 응용 분야에서 사용 될 수 있는 대규모 머신러닝 모델 ex) gpt-3,gpt-4,bert, roberta
1. 범용성
2. 전이학습 - 사전 학습된 모델을 사용(fine tuning은 사전 학습된 모델에 새로운 데이터 학습, 보통 학습률을 낮게 설정)
3. 데이터 효율성 : 더 작은 양으ㅏ ㅣ데이터로도 높은 성능을 낼 수 있음
4. 다양한 응ㅇ용 : 이미지 인식, 음성인식 ,추천 시스템에도 활용 가능
5. 윤리적, 사회적 이슈 - 편향성, 해석 가능성, 데이터 프라이버시 문제 수반 가능
- openai, google은 유료, llama는 무료
- finetuning 해서 사용

## Reinforcement Learning from human feedback(문제가 되는 발언을 없애기)
- llm


foundation model -> Reinforcement Learning from human feedback

