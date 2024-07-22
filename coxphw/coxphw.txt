# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Weighted Estimation in Cox Regression Use coxphw With (In) R Software
install.packages("coxphw")
library("coxphw")
coxphw = read.csv("https://raw.githubusercontent.com/timbulwidodostp/coxphw/main/coxphw/coxphw.csv",sep = ";")
# Estimation Weighted Estimation in Cox Regression Use coxphw With (In) R Software
coxphw <- coxphw(Surv(time, status) ~ radiation, data = coxphw, template = "AHR")
summary(coxphw)
# Weighted Estimation in Cox Regression Use coxphw With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished