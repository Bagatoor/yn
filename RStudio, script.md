# yn
sze=scan(file = "sze1950.txt")
sze.norm = rnorm(length(sze), mean(sze), sd(sze))
plot( sze, type = "l", xlab = "t [nap]", ylab = "h [cm]", lwd = 2); lines(sze.norm)
summary(sze)
sd(sze)*2
IQR(sze)
summary(sze.norm)
quantile(sze)
set.seed(9041)
rnorm(length(sze), mean(sze), sd(sze))
y=rnorm(length(sze), mean(sze), sd(sze))
summary(y)
