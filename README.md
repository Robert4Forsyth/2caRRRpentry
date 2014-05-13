2caRRRpentry
=============

Rob I am now! editing your file!! how awesome is this. 

testfiles from software carpentry workshop
does this make a changes? Success or not?  I am hungry
Finakl version


gDat  <- read.delim("gapminderDataFiveYear.txt")


gDat  <- read.delim("gapminderDataFiveYear.txt")

ifun <- function(data){
fit <- lm(lifeExp~year, data = data)
coef(fit)
ifun <- function(data){
fit <- lm(lifeExp~year, data = data)
coef(fit)
## Create a subset gDat
Uganda_gDat  <- subset(gDat, country = "Uganda")
Uganda_gDat  <- subset.data.frame(gDat, country = "Uganda")
Uganda_gDat  <- subset.data.frame(gDat, country = "Uganda")
Uganda_gDat  <- subset(gDat, country == "Uganda")
str(Uganda_gDat)
library(plyr)
library(plyr)
(gDat, ~country, ifun)
ddply(gDat, ~ country, ifun)
ifun <- function(data){
fit <- lm(lifeExp~year, data = data)
coef(fit)
}
ddply(gDat, ~ country, ifun)
##Irenez and jennyz solution
ifun <- function(data){
fit <- lm(lifeExp ~ I(year-1952, data = data)
coef(fit)
}
ddply(gDat, ~ country, ifun)
##Irenez and jennyz solution
ifun <- function(data){
fit <- lm(lifeExp ~ I((year-1952), data = data)
coef(fit)
}
ddply(gDat, ~ country, ifun)
##Irenez and jennyz solution
ifun <- function(df){
fit <- lm(lifeExp ~ I((year-1952), df)
return (coef(fit))
}
ifun <- function(df){
fit <- lm(lifeExp ~ I((year-1952), df)
return (coef(fit))
}
ifun <- function(df){
fit <- lm(lifeExp ~ I((year-1952), df)
return(coef(fit))
}
ifun <- function(df) {
fit <- lm(lifeExp ~ I((year-1952), df)
return(coef(fit))
}
gDat  <- read.delim("gapminderDataFiveYear.txt")
library(ggplot2)
jfun <- function(df){
fit <- lm(lifeExp~I(year-1952),df)
return(coef(fit))
}
library(plyr)
ddply(gDat, ~ country, ifun)
library(plyr)
ddply(gDat, ~ country, ifun)
ddply(gDat, ~ country, jfun)
x <- subset(gDat, country=="Uganda")
ggplot(x, aes(x=year, y=lifeExp))+geom_point()+geom_smooth(method="lm")
intercept_slope(x)
x <- subset(gDat, country=="Uganda")
ggplot(x, aes(x=year, y=lifeExp))+geom_point()+geom_smooth(method="lm")intercept_slope(x)
