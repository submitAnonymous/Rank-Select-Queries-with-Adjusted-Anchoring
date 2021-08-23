# Rank-Select-Queries-with-Adjusted-Anchoring

https://github.com/simongog/sdsl-lite sdsl-lite framwork is used in the implementation. Thus, you need to have sdsl-lite installed to run the RSAA.

You can compile with 

g++ main.cpp -O3 -lsdsl -o RSAA -I /sdsl-lite-include-file-directory/ -L /thr-directory-including-the-sdsl-lib/ -std=c++17 -march=native 

Your CPU should be supporting the popcnt,pdep, tzcnt instrcutions.

The program accepts as input either the number files GOV2, URL, 5GRAM, DNA provided in https://github.com/aboffa/Learned-Rank-Select-ALENEX21 or the randomly generated bitmaps by the program. 

RSAA 0 size-of-the-random-bitmap-in-megabits s_parameter 

RSAA 1 s_parameter 
 
You can download the datasets GOV2, URL, 5GRAM, DNA from the links provided in https://github.com/aboffa/Learned-Rank-Select-ALENEX21. 
You can feed the files directly to the RSAA program via the command line 
