# Data-Frame-Assignment
> Name <-c("jeb","donald","ted","marco","carly","hillary","berine")
> ABC_POLITICAL_POLLS_RESULTS <- c(4,62,51,21,2,14,15)
> CBS_POLITICAL_POLLS_RESULTS <- c(12,75,43,19,1,21,19)
> election_data <- data.frame(Name,ABC_POLITICAL_POLLS_RESULTS,CBS_POLITICAL_POLLS_RESULTS)
> print(election_data)
     Name ABC_POLITICAL_POLLS_RESULTS CBS_POLITICAL_POLLS_RESULTS
1  jeb                           4                          12
2  donald                    62                          75
3  ted                          51                          43
4  marco                     21                          19
5  carly                         2                           1
6 hillary                      14                          21
7  berine                      15                          19
> summary(election_data)
     Name           ABC_POLITICAL_POLLS_RESULTS
 Length:7           Min.   : 2.00              
 Class   :character   1st Qu.: 9.00              
 Mode  :character   Median :15.00              
                    Mean   :24.14              
                    3rd Qu. :36.00              
                    Max.   :62.00              
 CBS_POLITICAL_POLLS_RESULTS
 Min.   : 1.00              
 1st Qu.:15.50              
 Median :19.00              
 Mean   :27.14              
 3rd Qu.:32.00              
 Max.   :75.00              
