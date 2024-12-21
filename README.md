# linemap
#Maps a value in a linear line

def map(val,x1,y1,x2,y2):
    y=(y2-y1)/(x2-x1)*val - ((y2-y1)/(x2-x1)*x1)+y1
    return y

