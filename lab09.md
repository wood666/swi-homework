top-down design算法&洗衣机算法
------

top-down design算法：

简单来说是“自顶向下，逐步求精的方法”，是一种计算机编程使用的算法思想，这种方法的思想就是对现在遇到的复杂或者抽象化的问题，进行纵向深入分解并使其被分解为多个简单的、具体化的、课解决的问题。


洗衣机算法：

SET the height of water equal to 0

SET the running time equal to 0

SET the steep time equal to 0

WHILE the height of water is not equal to the standarded height of water 

water_in_switch(open)

the hight of water equal to the get_water_volume()

IF  time_counter is not limited

halt(failure)

ENDIF

ENDWHILE

water_in_switch(close)

WHILE the steep time is not equal the standarded steep time

ENDWHILE

WHILE the running time is equal to time_counter

ENDWHILE

SET the running time equal to 0

WHILE the running time is not equal to  standarded running time 

motor_run(right)

the running time is equal to time_counter

ENDWHILE

WHILE the hight of water is not equal to 0

water_out_switch(open)

ENDWHILE 

water_out_switch(close)


halt(success)




