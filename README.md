# MLR
 to  To find the variables that are significant in the demand for shared bikes with the available independent variables using MLR.

# Multiple Linear Regression Example
data=read.csv(file.choose(),header=T)
fit <- lm(cnt~season+yr+mnth+holiday+weekday+workingday+weathersit+temp+atemp+hum+windspeed+casual+registered, data=data)
summary(fit)
# anova table
anova(fit) 

