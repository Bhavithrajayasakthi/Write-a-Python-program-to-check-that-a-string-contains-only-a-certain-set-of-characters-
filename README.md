# Write-a-Python-program-to-check-that-a-string-contains-only-a-certain-set-of-characters
import re

ip = "216.08.094.196"
string = re.sub('\.[0]*', '.', ip)
print(string)
output
 =======================
216.8.94.196

