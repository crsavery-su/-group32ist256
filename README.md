# -group32ist256
#requests and jason 
import requests 
import json 
# insert api 
response = requests.get("https://apimedic.net/symptomchecker/kb/healthservice-live/", "IssueID" )
if response.ok:
    issue = response.json()
print = issues

# numpy is use to calculate the risk factors 
import csv
with open('Doc.csv*document with factors that contribute to an illness*', 'r') as f:
    factors = list(cvs.reader(f, delimiter=';'))
print(Factors[:3])

# matplotlib

import matplotlib.pyplot as plt
fig = plt.figure(figsize=(20,10))
ax1 = fig.add_subplot(paitent )
ax2 = fig.add_subplot(diseases)
fig, (ax1, ax2) = plt.subplots(1,2, figsize=(20,10))
ax1.bar([1,2,3],[3,4,5])
ax2.barh([0.5,1,2.5],[0,1,2])
plt.show()
