### Bag of Words


#### Steps involved
- sentences given of diff. length
- first lower all the words of the sentences 
- then stop words applied -> it will delete the unnecessary words 
- then for each vocabulary the frequency will be calculated
- for example , he is a good boy , she is a good girl , boy and girl are good 
- here above the good - 3 , boy - 2 , girl - 2 ( from maximum to minimum )
- then here we do not have to choose all the words rather we have to choose few words whose freq is high
- and then do like one hot encoding
- there are two types binary bow or normal bow  , is normal it will count 1,2,3,4,...  and for binary it will be 0 or 1 .



### Advantages and Disadvantages of One Hot Encoding

#### Advantages
- Simple and Intuitive 
- Fixed size inputs 


#### Disadvantages
- sparse matrix problem is still there
- since order is not captured so it may convery different meaning
- out of vocabulary , means if new word has some word then it will not get captured 
- Semantic meaning is not get captured 
- for example , I am good  ......   I am not good   
- here if we capture it via vector makings then might be it will get similar meaning since 
- I am good [1 1 0 1]  and I am not good [1 1 1 1]   -> so this will give similar means get correlated but this is not true , both words are opposite . This cases are not handled in a good way via BOW .


