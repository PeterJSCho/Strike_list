# Strike_list
using range function make strikes list

min_strike=280
max_strike=300

w=[]
for strikes in range(min_strike*10, max_strike*10, 25 ):
    strikes=strikes/10
    w.append(strikes)

w
