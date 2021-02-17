library(dplyr)
library(tidyr)
library(ggplot2)
  
  Rural=read.csv(choose.files(), header=T)
  Rural

Rural %>% ggplot(aes(x=less.than.3km, fill=greater.than.3km))+
  geom_bar(color = "blue")+
  scale_fill_manual(values = colors)

ggplot(dfall, aes(x=">15&<64",y = 1273, fill=less.than.3km, group=greater.than.3km)) +
  geom_col(position = "dodge"
plot

Rural %>% ggplot(aes(x=No education, fill=greater.than.3km))+
  geom_bar(color = "blue")+
  scale_fill_manual(values = colors)

Rural %>% ggplot(aes())

summary(Rural)
           
# Generally am stack on how to pluck our category of interest say (Place of residence; Urban, Rural)..or do we draw the categories manually..pls help hapo

         
