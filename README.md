# Strike_list
using range function make strikes list

def strikes_list(min_strike, max_strike):
    st_list=[]
    st_min=int(min_strike*10)
    st_max=int((max_strike*10)+25)
    for x in range(st_min, st_max, 25):
        x= x/10
        st_list.append(x)
    return st_list

strikes_list(282.5,300)
