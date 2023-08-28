
# m0ai-Proglog 


active segment 
 - store file 
   - records 
 - index file
   - offset 
   - memory-mapped file

words
- record - 로그에 저장된 데이터 
- store file - 로그에 저장된 데이터를 저장하는 파일 
- index file - 로그에 저장된 데이터의 offset(index)을 저장하는 파일 
- segment - store file + index file 을 묶어서 말하는 추상적 개념
- log - 모든 세그먼트를 묶어서 말하는 추상적 개념
