# Team-project-for-ASC
19년도 겨울학기 고급통계계산 강좌 팀 프로젝트용 repository

# Project 개요
다변량 정규분포 함수를 다룰 때 대개의 경우 공분산의 역행렬 계산이 필수적이다. 특히 차원이 큰 다변량 정규분포에 대해 
공분산의 역행렬을 효율적으로 계산하는 알고리즘은 많은 학자들의 연구 대상이다. 본 프로젝트는 Cao et al.(2019)의 논문 
"Hierarchical-block conditioning approximations for high-dimensional multivariate normal probabilities."에 
수록된 방법론과 code를 실제로 구현하는 것이었다. 해당 논문의 방법론은 크게 세 가지 아이디어로 구성되어 있었다:
block-reordering, hierarchical Cholesky decomposition, bi-variate conditioning method
조원은 본인을 포함해 3명이었으며, 각자의 contribution은 아래와 같다. 나머지 조원 2명의 이름은 익명으로 처리하였다.

# Contribution 
양현석 : block reordering 과정에 대한 코드 작성 
이** : hierarchical Cholesky decomposition과 관련된 계산 과정에 대한 코드 작성
김** : bi-variate conditioning method를 적용한 계산 과정에 대한 코드 작성
