# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Multiplicative structural mean model Use msmm (OneSampleMR) With (In) R Software
install.packages("OneSampleMR")
library("OneSampleMR")
msmm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/OneSampleMR/main/msmm/msmm.csv",sep = ";")
# Estimation Multiplicative structural mean model Use msmm (OneSampleMR) With (In) R Software
msmm_1  <- msmm(Y1 ~ X1 | Z, data = msmm)
summary(msmm_1)
msmm_2 <- msmm(Y2 ~ X2 | G1 + G2 + G3, data = msmm)
summary(msmm_2)
# Multiplicative structural mean model Use msmm (OneSampleMR) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished