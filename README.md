# myline
#Maps a value into a linear line
#enter the required x value (Val)
#enter the first point coordinates(x1 and y1)
#enter the second point coordinates(x2 and y2)
#q is the resulting value (x value) of Val

def map(val,x1,y1,x2,y2):
    q=(y2-y1)/(x2-x1)*val - ((y2-y1)/(x2-x1)*x1)+y1
    return q

