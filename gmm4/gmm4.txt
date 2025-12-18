# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# GMM (Generalized Method of Moments) estimation Use gmm4 (momentfit) With (In) R Software
install.packages("momentfit")
library("momentfit")
# Estimation GMM (Generalized Method of Moments) estimation Use gmm4 (momentfit) With (In) R Software
gmm4 = read.csv("https://raw.githubusercontent.com/timbulwidodostp/gmm4/main/gmm4/gmm4.csv",sep = ";")
gmm4 <- gmm4(y ~ x1, ~ z1 + z2, vcov = "MDS", type = "iter", data = gmm4)
summary(gmm4)
# GMM (Generalized Method of Moments) estimation Use gmm4 (momentfit) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished