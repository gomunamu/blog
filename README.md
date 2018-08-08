## Reinforcement Learning in CVPR 2018 
- 개인적으로 볼만한 paper

(정리중)
1. SeedNet: Automatic Seed Generation with Deep Reinforcement Learning for Robust Interactive Segmentation
 : 한국인(서울대) 저자 논문, 강화학습을 이용해서 interactive한 segmentation 구현, 영상처리에서 강화학습이 어떻게 사용될지 잘 볼 수 있는 듯
2. Deep Progressive Reinforcement Learning for Skeleton-based Action Recognition 
 : 별짓 다 해도 안되던 action recognition을 강화학습으로 풀었다. 과연 실제 성능이? 근데, 평가용 데이터셋들이 내가 알던 것이 아니다;
3. Reinforcement Cutting-Agent Learning for Video Object Segmentation 
 : segmentation이랑 video에 적용된 강화학습이다. 아무래도 reward가 자주 있으면 학습이 잘 될 것 같긴 한데, reward를 자주 주는 것도 일이다.. 그러니 그런 과정이 자동으로 해결되는 게임부터 강화학습이 적용되었겠지.
4. Deep Reinforcement Learning of Region Proposal Networks for Object Detection
 : 이번엔 RPN을 강화학습으로 풀고, 이후 sequential한 네트워크(GRU)를 사용했다. 그냥 봐도 복잡해 보이는데 오컴의 면도날이 자꾸 생각나는건 인간 본능에 가까운 듯
5. Distort-and-Recover: Color Enhancement using Deep Reinforcement Learning
 : 이번에도 한국인 저자들이 쓴 페이퍼이다. 페이퍼 찾다 보면, 의료기술 업체인 루닛이 종종 보이는데 CVPR에도 논문을 냈다. 그외 카이스트, 어도비 소속. 강화학습을 video나 segmentation에 적용하지 않은 paper라서(좀 특이해 보여서?) top5에 (내 맘대로) 선정했다.
