# hello-world
just a test for my joural of github
##
library(tidyverse)
library(nycflight13)
flights%>%group_by(year,month,day)%>%
filter(arr_delay>30)%>%ggplot(aes(x=arr_delay)+geom_histogram()
