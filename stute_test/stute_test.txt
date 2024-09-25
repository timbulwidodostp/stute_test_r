# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Stute (1997) linearity test Use stute_test (StuteTest) With (In) R Software
install.packages("StuteTest")
library("StuteTest")
stute_test = read.csv("https://raw.githubusercontent.com/timbulwidodostp/stute_test_r/main/stute_test/stute_test.csv",sep = ";")
# Estimation Stute (1997) linearity test Use stute_test (StuteTest) With (In) R Software
stute_test(df = stute_test, Y = "Y", D = "D")
stute_test(df = stute_test, Y = "Y", D = "D", group = "G", time = "T")
stute_test(df = stute_test, Y = "Y", D = "D", group = "G", time = "T", baseline = 1)
# Stute (1997) linearity test Use stute_test (StuteTest) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished