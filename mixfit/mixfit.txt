# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finite Mixture Modeling for Raw Data and Binned Data Use mixfit (mixR) With (In) R Software
install.packages("mixR")
library("mixR")
# Estimate Finite Mixture Modeling for Raw Data and Binned Data Use mixfit (mixR) With (In) R Software
mixfit = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mixfit/main/mixfit/mixfit.csv",sep = ";")
mixfit_ <- as.matrix(mixfit)
mixfit_normal <- mixfit(mixfit_, ncomp = 2, family = "normal")
mixfit_weibull <- mixfit(mixfit_, ncomp = 2, family = "weibull")
mixfit_gamma <- mixfit(mixfit_, ncomp = 2, family = "gamma")
mixfit_lnorm <- mixfit(mixfit_, ncomp = 2, family = "lnorm")
mixfit_normal
mixfit_weibull
mixfit_gamma
mixfit_lnorm
# Finite Mixture Modeling for Raw Data and Binned Data Use mixfit (mixR) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished