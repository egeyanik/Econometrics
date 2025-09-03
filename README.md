#### Homework #1 ####
#### Student: EGE YANIK ####

load("d_HHP2020_24.RData")

d_HHP2020_24[1:10,1:6]

attach(d_HHP2020_24)

summary(d_HHP2020_24)

summary(Age[Gender == "female"])

summary(Age[Gender == "male"])

summary(Age[Gender == "trans"])

summary(Age[Gender == "other"])

mean(Age[Gender == "female"])

sd(Age[Gender == "female"])

mean(Age[Gender == "male"])

sd(Age[Gender == "male"])

#### After looking at the summaries, I saw that the average ages of males and females are both in the early 50s, which makes sense since the survey includes many working-age and older adults. What caught my attention was the younger averages in the “trans” and “other” groups their mean ages are noticeably lower compared to male and female respondents. ####

#### Questions ####

1- Do college graduates earn more than high school graduates?
  
2- Do people without private health insurance report higher anxiety?
  
3- Does region matter for work loss?

