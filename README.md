# go-crypto-common
There are multiple reasons for me to open-source this repo which I will list below. I hope many more people will contribute tokens and decimals to this repo. 

My first reason for opening this repo is because the idea of it containing an ever growing collection of common crypto tokens such as Ether and Tether as k/v pairs in dedicated hashmaps excites me.. 

Futhermore, I hope to lower the barrier of entry for other developers that want to work with smart contracts as building up your own database of tokens and their decimals can be a pain.

Lastly, for archive node based analysis, using an API is often not feasible / too expensive and sometimes it would be preferable to use hashmaps for decimal retrieval instead. 

 # 1. Is it true that using hashmaps for decimal retrieval can be preferable when execution speed is crucial?

        Yes, in some scenarios, utilizing hashmaps for decimal retrieval can offer improved performance compared to making API calls. Retrieving data from an API involves network communication and potential latency, which can introduce overhead. On the other hand, if you have pre-loaded and efficiently structured hashmaps with the necessary decimal data, accessing that data locally can be faster.

# 2. Is a hashmap always faster than an API?
        
        It's important to note that the performance comparison between hashmaps and APIs is not absolute and depends on various factors. The efficiency of hashmaps depends on factors such as the size of the hashmap, the data structure used, the algorithm for accessing the data, and the memory and processing power of the system. APIs can vary in performance based on factors such as network latency, server load, and the complexity of the API endpoints.



