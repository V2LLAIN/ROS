# ROS 과제
![image](https://github.com/V2LLAIN/ROS/assets/104286511/76ec9923-2078-49ed-b112-437f7d2265db)

### workspace 생성
    cd ~

### p6과 catboostclassifier의 learning_rate 조정
    python train.py --p6_learning_rate 2e-4 --cat_learning_rate 2e-4

### VOCAB_SIZE, MAX_LEN 조정
    python train.py --MAX_LEN 1024 --VOCAB_SIZE 31000
