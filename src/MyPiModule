'''
A python module to exhibit the use of the __main__ name.
'''

import numpy as np
import math
def gottfriedPi(precetion):
    pi = 0
    for n in range(1,precetion):
        if 1%2 == 1:
            pi += 1/((2*n)-1)
        else:
            pi-= 1/((2*n)-1)
    pi*= 4
    return pi
def sharpPi(precition):
    pi = 0
    for n in range(0,precition):
        number = 2*(3**(1/2-n))
        number =number / ((2*n)+1)
        if 1%2 == 0:
            number = -number
        pi += number
    return pi
def montecarloPi (precition):
    pi = 0
    count = 0
    for n in range(0,precition):
        x = np.random.random()
        y = np.random.random()
        if math.sqrt((x**2) + (y**2)) <= 1:
            count += 1
    area = count/precition
    pi = 4*area
    return pi
# Main Function

