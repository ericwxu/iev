1. Copy the “comparison” folder to the default working directory of R.
2. Install MDR package.
3. Install iev package.
4. To compare MDR, BOOST and IEV in the simulated data set, run "comparison-different noise iteration 1000-MDR-BOOST-IEV" script.
5. To compare MDR, BOOST and IEV in the real data set, run "comparison-choosedata-SCC-MDR-BOOST" script. you can modify two parameters of necessaryconditions function: "consistencythreshold" and “coveragethreshold”. you can also modify two parameters of iev function: "iteration" and “consistencythreshold”.
6. The data is stored in the "data" directory.
7. View the results in the "result" directory or in the R window.
8. To generate simulated data with strict, epistatic models of different noise, employ generatedata function.