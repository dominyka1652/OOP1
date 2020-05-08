### Usage of version v1 

Open cmd in file location then enter "make" and enter "main"

1. The program asks you if you want to create files (write "sukurti") or not (write "nenoriu")
2. If you choose yes:
    - enter the number of files you want to generate
    - enter the number of sudents
    - enter the number of homeworks
    - enter "vidurki" if you want to get the average or enter "mediana" if you want to get median.   
    - if you choose more ten 1 file, then the program asks you to enter everything that is mentioned from b)
3. If you choose no:
    - enter "ivesti" if you want to input data manually or enter "nuskaityti" if you want to read from a file:
      - if you choose "ivesti" then look ->usage of a v0.3 version
      - if you choose "nuskaityti" enter name of the file without ".txt"</h6>
     - enter the number of marks without exam </h6>
     - write "vidurki" if you want to get an average or "mediana" if you want to get a median
4. You will see how much time it takes to read data from a file and separate into two groups.

#### My PC :
1. CPU - Intel core i7
2. RAM - 8GB
3. HDD - 1TB


|
|         |Read1000|Separate|   Read   | Separate|  Read  | Separate  |  Read  |  Separate  |
|---------|--------|--------|----------|---------|--------|-----------|--------|------------|
| Vector1 |0.01097 |    0   |0.074799  |0.005017 |0.76503 |0.053859   |0.76503 |0.053859    |
| list1   |0.008974|0.000997|0.082778  |0.010971 |0.813433|0.130168   |8.53119 |1.32708     |
| deque1  |0.009004|0.000997|0.0817821 |0.024934 |0.816977|0.139657   |8.38504 |1.49906     |
| Vector2 |0.008011| 0.001  |0.074751  |0.007982 |0.782138|0.101004   |7.89466 |1.06472     |
| list2   |   0    |    0   |0.062459  |0.008042 |0.793721|7.07003    |7.07003 |1.11067     | 
| deque2  |0.015625|    0   |0.123653  |0.019627 |0.904572|0.126269   |7.96267 |1.39118     |
| vector3 |  0     |    0   |0.060071  |0.010014 |0.78306 |0.117686   |7.54064 |1.18951     |  


##### Results:
Which (vector, deque or list) is the fastest?
1. Reading from a file:
    - Nr1. list
    - Nr2. vector
    - Nr3. deque
2. Separation:
    - Nr1. vector
    - Nr2. list
    - Nr3. deque
    
##### Vector with and without some algorithms
1. Reading from a file:
    - Nr1. with
    - Nr2. without
2. Separation:
    - Nr1. without
    - Nr2. with
